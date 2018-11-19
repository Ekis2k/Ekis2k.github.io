---
layout: post
title:  "Open Graph"
date:   2018-11-19 11:35:00 +0100
categories: blogpost
---

Open Graph är ett sätt att definera vad som visas när sidan delas på sociala medier. Det man behöver göra är att lägga till <meta> taggar i sidans head och fylla i infon som man vill ska visas. Det som behövs i meta-taggen är `property` som berättar vilken typ av info som det är och `content` som är värdet.

## Det är fyra obligatoriska property-typer.

---

1. `og:type` - Vad är det som delas?
2. `og:title` - Titeln på vad som delas
3. `og:url` - Url till sidan som delas
4. `og:img` - Url till bilden som visas

---

Kolla [opengraph](http://ogp.me/) för mer indepth info om hur det fungerar.

Detta är hur jag gjorde och lade in i sidans head.

```
<head>
    <meta property="og:title" content="Examination 1" />
	<meta property="og:type" content="ekis2k.examination" />
	<meta property="og:url" content="http://www.github.com/Ekis2k" />
	<meta property="og:image" content="https://jekyllrb.com/img/logo-2x.png" />
</head>
```
