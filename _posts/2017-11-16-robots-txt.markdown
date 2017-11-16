---
layout: post
title:  "robots.txt"
date:   2017-11-16 12:00:00 +0100
categories: jekyll update
comments: true
---
För att kunna hantera sökrobotar på webben finns det en fil som heter robots.txt.

Om man saknar denna fil på webbservern kommer sökrobotarna att lägga till allt innehåll som finns på servern till sin sökmotor.

Detta är ju inte särskilt klokt om man t.ex. har underkataloger som bara inkluderar innehåll till en annan sida. Man kan säga att robots.txt är en av delarna för att sökoptimera sin webbplats mot sökmotorn.

I robots.txt definierar man vilka kataloger och eller filer som sökroboten **inte** får söka i och vilka sökrobotar som ska få tillåtas söka på webbplatsen. Man kan till och med hindra sökrobotar från att söka på webbplatsen över huvudtaget.

På denna webbplats har jag valt att exkludera allt innehåll i mappen */assets/* där jekyll har lagt min css-fil och bilder.
