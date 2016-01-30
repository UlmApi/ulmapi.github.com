---
layout: post
categories: project
date: 2015-02-21 13:00:00
title: "Projekt: Kleinerspatz"
img: "/images/projects/kleinerspatz.png" 
imglarge: "/images/projects/large/kleinerspatz-large.png"
imgalt: "Kleinerspatz Karte"
imglink: http://www.ulmapi.de/kleinerspatz
---

Wo in Ulm sind noch Kita-Plätze verfügbar? 
**Update 2016-01-11:** Karte außer Betrieb.  
[Zur Karte!](http://www.ulmapi.de/kleinerspatz)  

*Aktuell: Die Ausgangsseite der Stadt wurde leider dahingehend verändert, dass unser Parser nicht mehr funktioniert. Bis auf weiteres ist die Karte daher leider außer Funktion.*

Auf dieser Karte werden die verfügbaren KiTa-Plätze in der Stadt Ulm angezeigt.
Die Daten der KITA-Plätze kommen von der [Übersichtsseite der Stadt Ulm](http://www.ulm.de/ulm/stadt_ulm_01.c.72078.de/), und werden von uns (un)regelmäßig gescrapet und in der Anwendung eingetragen. Die Karte wird auf Basis von [OpenStreetMap](http://openstreetmap.org/) mittels des Tile-Servers von [Code For Germany](http://codefor.de/) generiert.

Einige Zeit nachdem wir dieses Projekt gestartet haben, hat die Stadt ihr Geodatenportal [maps.ulm.de](maps.ulm.de/GeoportalUlmWebapp/client/maps/) verbessert; dort werden jetzt Ort und Träger der jeweiligen KiTas angegeben. Die Träger sind nicht über die Suche der Stadt zu erreichen und sind deswegen nicht auf der Kleinerspatz-Karte zu sehen.

## Weitere Links

 * [github: ulmapi/kleinerspatz](https://github.com/UlmApi/kleinerspatz). Die Daten kann jeder lokal von der Stadtseite abrufen – einfach das `encodekitas.pl`-Script ausführen (bei einer Fehlermeldung einfach noch mal ausführen). Die Koordinaten für den Brombeerweg 4 sind inkorrekt auf der Ulmer Seite eingetragen; der tatsächliche Ort ist lat 9.951167, lon 48.405928. Dieser Fehler wurde der Stadt mehrfach gemeldet – aber Behördenmühlen mahlen langsam…
 
## Projektstatus

 * Prototyp
 * laufend
