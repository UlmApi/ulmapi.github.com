---
layout: post
categories: news
date: 2016-03-05 18:29:00
title: "Die inoffizielle Park-API für die Uni Ulm"
img: "/images/news/park_api.jpg"
imglarge: "/images/news/large/park_api.jpg"
imgalt: "So sieht das aus"
---

Wir hatten viel Spaß mit einer undokumentierten Parkplatz-API – und den Versuchen der Herausgeber, sie zuzunageln ;)

Alles begann am 1. März mit einer Mail an alle Studierende, die freudig von einer neuen Parkauslastungs-App für iOS und Android erzählte, und natürlich auch [einer Web-App, auf die man hier klicken solle](http://tsu-app.rrooaarr.biz/front/). Oder so ähnlich ;)

![„Hier verlinken!“](/images/news/2016-03/studierende-mail.png)

Wie sich das für Freund\*innen freier Daten und ihrer Nachnutzung gehört, dauerte es auf unserer Mailingliste genau 15 Minuten, bis ein erstes „Grrrr! Wir haben die Daten bisher noch nicht bekommen, oder?“ über den Verteiler lief – und kurz danach [war auch der Endpunkt der „SOAP“-Schnittstelle](http://tsu-app.rrooaarr.biz/front/soap.php?counterid=10021) gefunden.

Damit wäre die Geschichte eigentlich so gut wie zu Ende gewesen, hätte nicht direkt so etwas wie ein Wettrüsten eingesetzt. Zuerst wurde der API-Endpunkt „umgezogen“ und unter dem alten URL ein [Uncle-Sam-Bild](https://commons.wikimedia.org/wiki/File:Unclesamwantyou.jpg) angezeigt. Danach wurde ein `X-Requested-With: XMLHttpRequest`-Header nötig, um nicht von der API abgewimmelt zu werden. Und am folgenden Mittag war dann auch `tsu-app.rrooaarr.biz` als Referer nötig – bevor die API dann wieder in den Urzustand versetzt wurde, weil irgendwann im Lauf des Tages auch die offizielle Web-App vor lauter Vernagelung keine Belegungszahlen für die Parkplätze mehr ausgeben konnte. Lediglich der Server von [Seder](https://twitter.com/_seder_), mit dem er eine Belegungsverlaufkurve abgraste, blieb per IP-Sperre ausgesperrt.

<blockquote class="twitter-tweet" data-lang="en"><p lang="de" dir="ltr"><a href="https://twitter.com/b_erb">@b_erb</a> <a href="https://twitter.com/_stk">@_stk</a> Hab auch mal ein bisschen mitgeloggt. Hier die Parkplatzauslastung seit heute Nachmittag. <a href="https://t.co/AxxlEkhUA9">pic.twitter.com/AxxlEkhUA9</a></p>&mdash; Seder (@_seder_) <a href="https://twitter.com/_seder_/status/704709859514716160">March 1, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Mittlerweile gibt es [auch eine offizielle iOS-App](https://itunes.apple.com/de/app/duu-parken/id1081039841?mt=8) – es lohnt sich, die anderen Bewertungen der lobenden Rezensenten anzusehen ;)

Für künftige Aufträge legen wir der Parkraumbewirtschaftung und der ausführenden Firma [die momentan entstehenden Standards zu Park-APIs ans Herz](https://github.com/offenesdresden/ParkAPI). So können die Daten auch sinnvoll von Dritten nachgenutzt und vielleicht auch zu barrierefreier nutzbaren Apps führen.
