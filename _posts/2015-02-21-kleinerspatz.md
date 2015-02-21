---
layout: post
categories: project
date: 2015-02-21 13:00:00
title: "Projekt: Kleinerspatz"
img: "/images/projects/kleinerspatz.png" 
imgalt: "Kleinerspatz Karte"
---

Wo in Ulm sind noch Kita-Plätze verfügbar?  
**Upate:** Daten aktualisiert.  
[Zu der Anwendung!](http://www.ulmapi.de/kleinerspatz)  

Auf diese Karte werden die verfügbaren KITA-Plätze in der Stadt Ulm angezeigt.
Die Daten der KITA-Plätze kommen von der [Übersichtsseite der Stadt Ulm](http://www.ulm.de/ulm/stadt_ulm_01.c.72078.de/), und werden von uns abgerufen und in der Anwendung eingetragen. Die Karte wird auf Basis von [OpenStreetMap](http://openstreetmap.org/) mittels des Tile-Servers von [Code For Germany](http://codefor.de/) generiert.

Einige Zeit nachdem wir dieses Projekt gestartet haben hat der Stadt [maps.ulm.de](maps.ulm.de/GeoportalUlmWebapp/client/maps/) verbessert; dort werden jetzt Ort und Träger der jeweiligen KITAs angegeben. Die Träger sind nicht über die Suche der Stadt zu erreichen und sind deswegen nicht auf der Kleinerspatz zu sehen.

Die Code zu dem Projekt findet man auf [der github Projekt-Seite](https://github.com/UlmApi/kleinerspatz). Die Daten kann jeder lokal von der Stadtsseite abrufen mittels das `encodekitas.pl` script (bei ein Fehlermeldung einfach noch mal ausführen). Die Koordinaten für den Brombeerweg 4 sind inkorrekt auf der Ulmer Seite eingetragen; den tatsächlichen Ort ist lat 9.951167, lon 48.405928.
