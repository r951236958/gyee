---
layout: post
title:  "家有大虎 - 林虎"
categories: gyee
---

## 基礎屬性

![基礎素質][基礎素質]

生命|速度|物攻|物防|法防
--|--|--|--|--
575|62|61|166|143

## 技能說明

###	信仰之力

精通 消耗: 30點法力 無冷卻

![信仰之力][信仰之力]

林虎在行動後，如果自身當前法力值不小於30點，則為自身添加3層【信仰之力】效果。

【信仰之力】: 效果生效期間，常駐降低15%自身受到的任何傷害（該能力不受精通屬性加成），同時受到精通效果影響，額外降低 10.00%（固定加成 10.00% + 精通加成 0.00%）。此外，林虎在受到直接攻擊後，會自動移除 1 層【信仰之力】。效果結束時會以每層15點的x法力值對持有者進行恢復。持續至下次行動前自動消失。

###	鐵山靠	無能流

普攻 近戰 消耗: 15點法力 無冷卻

![鐵山靠][鐵山靠]

林虎發動神力，對1名敵人造成物理攻擊*94%的物理傷害。並為自身添加1層【神格】效果，有50%的機機率會額外添加1層。

【神格】: 效果生效期間，可不斷進行疊加，最多可疊加4層。在施放技能【怒虎】時，每層【神格】可為自身恢復30點法力值。持續至戰鬥結束。

>	下一級屬性
>	技能傷害提升21%


被動效果【神格】

### 神力灌注	地能流

主動	遠程	消耗	消耗: 75法力 無冷卻

![神力灌注][神力灌注]

林虎借助天神之力，對首要敵方目標造成物理攻擊*226%的物理傷害，並有68%的機率對隨機1-3個非首要目標施加【膜拜】效果。

【膜拜】: 效果生效期間，喪失對角色的控制權，直至持續時間結束或受到任何刑事的傷害後脫離該效果。持續2回合。

>	下一級屬性
>	減傷提傷20%

**被動效果** 【神威】【未知】

### 怒虎	地能流

主動	遠程	消耗: 8法力	冷卻: 4回合

![怒虎][怒虎]

林虎運轉氣息，對1名敵人造成物理攻擊*296%的傷害，並有100%的機率對目標施加【膜拜】效果。

同時，移除自身當前所有【神格】效果，並為自身恢復法力值。

【膜拜】: 效果生效期間，喪失對角色的控制權，直至持續時間結束或受到任何刑事的傷害後脫離該效果。持續2回合。

【神格】: 效果生效期間，可不斷進行疊加，最多可疊加4層。在施放技能【怒虎】時，每層【神格】可為自身恢復30點法力值。持續至戰鬥結束。

>	下一級屬性
>	技能傷害提升27%

被動效果【未知】【未知】【未知】

[基礎素質]: {{ "/assets/img/Nekojishi_2.jpg" | relative_url }}
[鐵山靠]: {{ "/assets/img/Nekojishi_4.jpg" | relative_url }}
[神力灌注]: {{ site.baseurl }}/assets/img/Nekojishi_3.jpg
[怒虎]: {{ "/assets/img/Nekojishi_1.jpg" | relative_url }}
[信仰之力]: {{ "/assets/img/Nekojishi_5.jpg" | prepend: site.baseurl  }}

#### 圖片顯示測試

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
