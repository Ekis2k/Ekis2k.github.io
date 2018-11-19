---
layout: post
title:  "Robots.txt and how i did it"
date:   2018-11-19 12:15:44 +0100
categories: blogpost
---
Robot.txt är en textfil som anger vad sökmotorer som söker efter när de söker efter din webbsida. Sökmotorer letar automatiskt efter din robots.txt för att se vad du har tillåtit.
Den här filen är viktig för att lägga in din rotkatalog.

Min Robots.txt ser ut som följande.
```
User-agent: Googlebot
Disallow: 
User-agent: MSNBot
Disallow: 
User-agent: Slurp
Disallow: 
User-agent: *
Disallow: /
```

I min fil så har jag valt att ge tillgång till Google, MSN Search och Yahoo. Om man inte skulle ge tillgång till vissa robotar så finns risken att sidan hamnar längre ner i sökresultaten. Resten av robotarna har inte tillgång och det visas med
```
User-agent: *
Disallow: /
```
