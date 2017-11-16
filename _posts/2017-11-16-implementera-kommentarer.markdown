---
layout: post
title:  "Implementera kommentarer"
date:   2017-11-16 12:30:00 +0100
categories: jekyll update
comments: true
---
För att implementera kommentarsmöjligheter på denna webbplats valde jag verktyget [Disqus](http://disqus.com){:target="_blank"} då det redan finns förberett för användning i Jekyll.

Det enda jag behövde göra var att justera ett antal variabler i *config.yml*-filen som hänvisar till webbplatsens url och vilket konto på disqus som ska användas. Därefter var det bara att lägga till variabeln comments: true i "front-mattern" på de sidor där jag ville ha kommentarsmöjlighet.
