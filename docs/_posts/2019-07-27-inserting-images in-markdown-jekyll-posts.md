---
layout: post
title:  "在Jekyll靜態網頁中插入圖片"
categories: jekyll
---

## 使用網站自定義變量設置為圖片網址

```markdown
![怒虎]({{ "/assets/img/Nekojishi_1.jpg" | relative_url }})
![怒虎]({{ "/assets/img/Nekojishi_1.jpg" | absolute_url }})
![怒虎]({{ "/assets/img/Nekojishi_1.jpg" | prepend: site.baseurl }})
![怒虎]({{ site.baseurl }}/assets/img/Nekojishi_1.jpg)
![怒虎]({{ site.url }}/assets/img/Nekojishi_1.jpg)
![怒虎](../assets/img/Nekojishi_1.jpg)
```

![怒虎]({{ "/assets/img/Nekojishi_1.jpg" | relative_url }})
![怒虎]({{ "/assets/img/Nekojishi_1.jpg" | absolute_url }})
![怒虎]({{ "/assets/img/Nekojishi_1.jpg" | prepend: site.baseurl }})
![怒虎]({{ site.baseurl }}/assets/img/Nekojishi_1.jpg)
![怒虎]({{ site.url }}/assets/img/Nekojishi_1.jpg)
![怒虎](../assets/img/Nekojishi_1.jpg)
