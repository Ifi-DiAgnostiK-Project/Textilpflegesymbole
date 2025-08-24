<!--
repository: "https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole"
author: "Volker Göhler, Niklas Werner"
email: "volker.goehler@informatik.tu-freiberg"
version: "0.2.4"
edit: true
title: "DiAgnostiK ISO 3758:2023 Textilpflegesymbole Makros"
tags: "Wissensspeicher"

@diagnostik_image: <img src='@0/@1' alt='@1' style='height: @2rem'>

@style
img {
 max-height: fit-content;
}
@end
@Bleichsymbole.licence: Bildquellen: © by GINETEX GERMANY, www.ginetex.de


@Bleichsymbole.Bleichen_erlaubt.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Bleichsymbole/Bleichen-erlaubt.jpg
@Bleichsymbole.Bleichen_erlaubt: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Bleichsymbole/Bleichen-erlaubt.jpg,@0)

@Bleichsymbole.Nicht_bleichen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Bleichsymbole/Nicht-bleichen.jpg
@Bleichsymbole.Nicht_bleichen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Bleichsymbole/Nicht-bleichen.jpg,@0)

@Bleichsymbole.Sauerstoffbleichen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Bleichsymbole/Sauerstoffbleichen.jpg
@Bleichsymbole.Sauerstoffbleichen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Bleichsymbole/Sauerstoffbleichen.jpg,@0)
@Buegelsymbole.licence: Bildquellen: © by GINETEX GERMANY, www.ginetex.de


@Buegelsymbole.Buegeln_erlaubt.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Buegelsymbole/Buegeln-erlaubt.jpg
@Buegelsymbole.Buegeln_erlaubt: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Buegelsymbole/Buegeln-erlaubt.jpg,@0)

@Buegelsymbole.Buegeln_geringe_Temperatur.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Buegelsymbole/Buegeln-geringe-Temperatur.jpg
@Buegelsymbole.Buegeln_geringe_Temperatur: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Buegelsymbole/Buegeln-geringe-Temperatur.jpg,@0)

@Buegelsymbole.Buegeln_hohe_temperatur.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Buegelsymbole/Buegeln-hohe-temperatur.jpg
@Buegelsymbole.Buegeln_hohe_temperatur: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Buegelsymbole/Buegeln-hohe-temperatur.jpg,@0)

@Buegelsymbole.Buegeln_mittlere_Temperatur.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Buegelsymbole/Buegeln-mittlere-Temperatur.jpg
@Buegelsymbole.Buegeln_mittlere_Temperatur: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Buegelsymbole/Buegeln-mittlere-Temperatur.jpg,@0)

@Buegelsymbole.buegeln_nicht_erlaubt.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Buegelsymbole/buegeln-nicht-erlaubt.jpg
@Buegelsymbole.buegeln_nicht_erlaubt: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Buegelsymbole/buegeln-nicht-erlaubt.jpg,@0)
@Reinigungssymbole.licence: Bildquellen: © by GINETEX GERMANY, www.ginetex.de


@Reinigungssymbole.keine_chemische_reinigung.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/keine-chemische-reinigung.jpg
@Reinigungssymbole.keine_chemische_reinigung: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/keine-chemische-reinigung.jpg,@0)

@Reinigungssymbole.keine_professionelle_nassreinigung.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/keine-professionelle-nassreinigung.jpg
@Reinigungssymbole.keine_professionelle_nassreinigung: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/keine-professionelle-nassreinigung.jpg,@0)

@Reinigungssymbole.Professionelle_Nassreinigung_moeglich.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Professionelle-Nassreinigung-moeglich.jpg
@Reinigungssymbole.Professionelle_Nassreinigung_moeglich: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Professionelle-Nassreinigung-moeglich.jpg,@0)

@Reinigungssymbole.professionelle_Reinigung_mit_Kohlenwasserstoffloesungsmittel.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/professionelle-Reinigung-mit-Kohlenwasserstoffloesungsmittel.jpg
@Reinigungssymbole.professionelle_Reinigung_mit_Kohlenwasserstoffloesungsmittel: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/professionelle-Reinigung-mit-Kohlenwasserstoffloesungsmittel.jpg,@0)

@Reinigungssymbole.Professionelle_reinigung.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Professionelle-reinigung.jpg
@Reinigungssymbole.Professionelle_reinigung: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Professionelle-reinigung.jpg,@0)

@Reinigungssymbole.Reinigung_mit_Perchlorethylen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Reinigung-mit-Perchlorethylen.jpg
@Reinigungssymbole.Reinigung_mit_Perchlorethylen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Reinigung-mit-Perchlorethylen.jpg,@0)

@Reinigungssymbole.Schonende_professionelle_Nassreinigung.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Schonende-professionelle-Nassreinigung.jpg
@Reinigungssymbole.Schonende_professionelle_Nassreinigung: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Schonende-professionelle-Nassreinigung.jpg,@0)

@Reinigungssymbole.Schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Schonende-Reinigung-mit-Kohlenwasserstoffloesungsmittel.jpg
@Reinigungssymbole.Schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Schonende-Reinigung-mit-Kohlenwasserstoffloesungsmittel.jpg,@0)

@Reinigungssymbole.Schonende_Reinigung_mit_Perchlorethylen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Schonende-Reinigung-mit-Perchlorethylen.jpg
@Reinigungssymbole.Schonende_Reinigung_mit_Perchlorethylen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Schonende-Reinigung-mit-Perchlorethylen.jpg,@0)

@Reinigungssymbole.Sehr_schonende_professionelle_Nassreinigung.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Sehr-schonende-professionelle-Nassreinigung.jpg
@Reinigungssymbole.Sehr_schonende_professionelle_Nassreinigung: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Sehr-schonende-professionelle-Nassreinigung.jpg,@0)

@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Sehr-schonende-Reinigung-mit-Kohlenwasserstoffloesungsmittel.jpg
@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Sehr-schonende-Reinigung-mit-Kohlenwasserstoffloesungsmittel.jpg,@0)

@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Perchlorethylen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Reinigungssymbole/Sehr-schonende-Reinigung-mit-Perchlorethylen.jpg
@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Perchlorethylen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Reinigungssymbole/Sehr-schonende-Reinigung-mit-Perchlorethylen.jpg,@0)
@Trocknersymbole.licence: Bildquellen: © by GINETEX GERMANY, www.ginetex.de


@Trocknersymbole.Nicht_trommeltrocknen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Nicht-trommeltrocknen.jpg
@Trocknersymbole.Nicht_trommeltrocknen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Nicht-trommeltrocknen.jpg,@0)

@Trocknersymbole.Trocknen_im_schatten.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen-im-schatten.jpg
@Trocknersymbole.Trocknen_im_schatten: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen-im-schatten.jpg,@0)

@Trocknersymbole.Trocknen_Leine_im_schatten.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen-Leine-im-schatten.jpg
@Trocknersymbole.Trocknen_Leine_im_schatten: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen-Leine-im-schatten.jpg,@0)

@Trocknersymbole.Trocknen_Leine.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen-Leine.jpg
@Trocknersymbole.Trocknen_Leine: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen-Leine.jpg,@0)

@Trocknersymbole.Trocknen_liegend_im_schatten.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen-liegend-im-schatten.jpg
@Trocknersymbole.Trocknen_liegend_im_schatten: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen-liegend-im-schatten.jpg,@0)

@Trocknersymbole.Trocknen_liegend.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen-liegend.jpg
@Trocknersymbole.Trocknen_liegend: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen-liegend.jpg,@0)

@Trocknersymbole.Trocknen_tropfnass_im_schatten.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen-tropfnass-im-schatten.jpg
@Trocknersymbole.Trocknen_tropfnass_im_schatten: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen-tropfnass-im-schatten.jpg,@0)

@Trocknersymbole.Trocknen_tropfnass.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen-tropfnass.jpg
@Trocknersymbole.Trocknen_tropfnass: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen-tropfnass.jpg,@0)

@Trocknersymbole.Trocknen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trocknen.jpg
@Trocknersymbole.Trocknen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trocknen.jpg,@0)

@Trocknersymbole.Trommeltrocknen_niedrige_Temperatur.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trommeltrocknen-niedrige-Temperatur.jpg
@Trocknersymbole.Trommeltrocknen_niedrige_Temperatur: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trommeltrocknen-niedrige-Temperatur.jpg,@0)

@Trocknersymbole.Trommeltrocknen_normale_Temperatur.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trommeltrocknen-normale-Temperatur.jpg
@Trocknersymbole.Trommeltrocknen_normale_Temperatur: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trommeltrocknen-normale-Temperatur.jpg,@0)

@Trocknersymbole.Trommeltrocknen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Trocknersymbole/Trommeltrocknen.jpg
@Trocknersymbole.Trommeltrocknen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Trocknersymbole/Trommeltrocknen.jpg,@0)
@Waschsymbole.licence: Bildquellen: © by GINETEX GERMANY, www.ginetex.de


@Waschsymbole.Handwaesche.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Waschsymbole/Handwaesche.jpg
@Waschsymbole.Handwaesche: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Waschsymbole/Handwaesche.jpg,@0)

@Waschsymbole.Nicht_waschen.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Waschsymbole/Nicht-waschen.jpg
@Waschsymbole.Nicht_waschen: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Waschsymbole/Nicht-waschen.jpg,@0)

@Waschsymbole.waschen_bei_30_grad_schonend.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Waschsymbole/waschen-bei-30-grad-schonend.jpg
@Waschsymbole.waschen_bei_30_grad_schonend: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Waschsymbole/waschen-bei-30-grad-schonend.jpg,@0)

@Waschsymbole.waschen_bei_30_grad_sehr_schonend.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Waschsymbole/waschen-bei-30-grad-sehr-schonend.jpg
@Waschsymbole.waschen_bei_30_grad_sehr_schonend: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Waschsymbole/waschen-bei-30-grad-sehr-schonend.jpg,@0)

@Waschsymbole.waschen_bei_30_grad.src: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img/Waschsymbole/waschen-bei-30-grad.jpg
@Waschsymbole.waschen_bei_30_grad: @diagnostik_image(https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/img,Waschsymbole/waschen-bei-30-grad.jpg,@0)
-->

# Link zu LiaScript
[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/makros.md)

> Diese Datei ist automatisch generiert und enthält Makros für die DiAgnostiK-Bilder der Gewerke.

# Anleitung
> Der Befehl zum einbinden eines Bildes lautet `@<Bereich>.<Name>(Größe)`.
> Hängt man statt der Größe `.src` an, so wird der Link zum Bild angezeigt. `@<Bereich>.<Name>.src`

- Der Bereich ist der Ordnername, in dem sich das Bild befindet.
- Der Name ist der Dateiname ohne Endung.
- Die Größe ist in Zeilen angegeben, die das Bild hoch sein soll.

Alle Bilder sowie ihre Bereiche und die Befehle um sie zu laden sind in den Tabellen weiter unten abgebildet.

**Die Anzeige benötigt LiaScript!**

## Beispiel

`@Trocknersymbole.Nicht-trommeltrocknen(10)`

@Trocknersymbole.Nicht-trommeltrocknen(10)

`@Trocknersymbole.Nicht-trommeltrocknen.src`

@Trocknersymbole.Nicht-trommeltrocknen.src

## Bereiche und Befehle

Im Nachfolgenden sind alle Bilder aller Bereiche und passende Befehle aufgelistet, die in dieser Sammlung enthalten sind. 


### Bleichsymbole


© by GINETEX GERMANY, www.ginetex.de


mit `@Bleichsymbole.licence` kann der Text ausgegeben werden.
<!-- START OF TABLE -->
|Bild|Name|Befehl|
|---|---|---|
|@Bleichsymbole.Bleichen_erlaubt(10)|_Bleichen erlaubt_|`@Bleichsymbole.Bleichen_erlaubt(10)`|
|@Bleichsymbole.Nicht_bleichen(10)|_Nicht bleichen_|`@Bleichsymbole.Nicht_bleichen(10)`|
|@Bleichsymbole.Sauerstoffbleichen(10)|_Sauerstoffbleichen_|`@Bleichsymbole.Sauerstoffbleichen(10)`|

### Buegelsymbole


© by GINETEX GERMANY, www.ginetex.de


mit `@Buegelsymbole.licence` kann der Text ausgegeben werden.
<!-- START OF TABLE -->
|Bild|Name|Befehl|
|---|---|---|
|@Buegelsymbole.Buegeln_erlaubt(10)|_Buegeln erlaubt_|`@Buegelsymbole.Buegeln_erlaubt(10)`|
|@Buegelsymbole.Buegeln_geringe_Temperatur(10)|_Buegeln geringe Temperatur_|`@Buegelsymbole.Buegeln_geringe_Temperatur(10)`|
|@Buegelsymbole.Buegeln_hohe_temperatur(10)|_Buegeln hohe temperatur_|`@Buegelsymbole.Buegeln_hohe_temperatur(10)`|
|@Buegelsymbole.Buegeln_mittlere_Temperatur(10)|_Buegeln mittlere Temperatur_|`@Buegelsymbole.Buegeln_mittlere_Temperatur(10)`|
|@Buegelsymbole.buegeln_nicht_erlaubt(10)|_buegeln nicht erlaubt_|`@Buegelsymbole.buegeln_nicht_erlaubt(10)`|

### Reinigungssymbole


© by GINETEX GERMANY, www.ginetex.de


mit `@Reinigungssymbole.licence` kann der Text ausgegeben werden.
<!-- START OF TABLE -->
|Bild|Name|Befehl|
|---|---|---|
|@Reinigungssymbole.keine_chemische_reinigung(10)|_keine chemische reinigung_|`@Reinigungssymbole.keine_chemische_reinigung(10)`|
|@Reinigungssymbole.keine_professionelle_nassreinigung(10)|_keine professionelle nassreinigung_|`@Reinigungssymbole.keine_professionelle_nassreinigung(10)`|
|@Reinigungssymbole.Professionelle_Nassreinigung_moeglich(10)|_Professionelle Nassreinigung moeglich_|`@Reinigungssymbole.Professionelle_Nassreinigung_moeglich(10)`|
|@Reinigungssymbole.professionelle_Reinigung_mit_Kohlenwasserstoffloesungsmittel(10)|_professionelle Reinigung mit Kohlenwasserstoffloesungsmittel_|`@Reinigungssymbole.professionelle_Reinigung_mit_Kohlenwasserstoffloesungsmittel(10)`|
|@Reinigungssymbole.Professionelle_reinigung(10)|_Professionelle reinigung_|`@Reinigungssymbole.Professionelle_reinigung(10)`|
|@Reinigungssymbole.Reinigung_mit_Perchlorethylen(10)|_Reinigung mit Perchlorethylen_|`@Reinigungssymbole.Reinigung_mit_Perchlorethylen(10)`|
|@Reinigungssymbole.Schonende_professionelle_Nassreinigung(10)|_Schonende professionelle Nassreinigung_|`@Reinigungssymbole.Schonende_professionelle_Nassreinigung(10)`|
|@Reinigungssymbole.Schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel(10)|_Schonende Reinigung mit Kohlenwasserstoffloesungsmittel_|`@Reinigungssymbole.Schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel(10)`|
|@Reinigungssymbole.Schonende_Reinigung_mit_Perchlorethylen(10)|_Schonende Reinigung mit Perchlorethylen_|`@Reinigungssymbole.Schonende_Reinigung_mit_Perchlorethylen(10)`|
|@Reinigungssymbole.Sehr_schonende_professionelle_Nassreinigung(10)|_Sehr schonende professionelle Nassreinigung_|`@Reinigungssymbole.Sehr_schonende_professionelle_Nassreinigung(10)`|
|@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel(10)|_Sehr schonende Reinigung mit Kohlenwasserstoffloesungsmittel_|`@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Kohlenwasserstoffloesungsmittel(10)`|
|@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Perchlorethylen(10)|_Sehr schonende Reinigung mit Perchlorethylen_|`@Reinigungssymbole.Sehr_schonende_Reinigung_mit_Perchlorethylen(10)`|

### Trocknersymbole


© by GINETEX GERMANY, www.ginetex.de


mit `@Trocknersymbole.licence` kann der Text ausgegeben werden.
<!-- START OF TABLE -->
|Bild|Name|Befehl|
|---|---|---|
|@Trocknersymbole.Nicht_trommeltrocknen(10)|_Nicht trommeltrocknen_|`@Trocknersymbole.Nicht_trommeltrocknen(10)`|
|@Trocknersymbole.Trocknen_im_schatten(10)|_Trocknen im schatten_|`@Trocknersymbole.Trocknen_im_schatten(10)`|
|@Trocknersymbole.Trocknen_Leine_im_schatten(10)|_Trocknen Leine im schatten_|`@Trocknersymbole.Trocknen_Leine_im_schatten(10)`|
|@Trocknersymbole.Trocknen_Leine(10)|_Trocknen Leine_|`@Trocknersymbole.Trocknen_Leine(10)`|
|@Trocknersymbole.Trocknen_liegend_im_schatten(10)|_Trocknen liegend im schatten_|`@Trocknersymbole.Trocknen_liegend_im_schatten(10)`|
|@Trocknersymbole.Trocknen_liegend(10)|_Trocknen liegend_|`@Trocknersymbole.Trocknen_liegend(10)`|
|@Trocknersymbole.Trocknen_tropfnass_im_schatten(10)|_Trocknen tropfnass im schatten_|`@Trocknersymbole.Trocknen_tropfnass_im_schatten(10)`|
|@Trocknersymbole.Trocknen_tropfnass(10)|_Trocknen tropfnass_|`@Trocknersymbole.Trocknen_tropfnass(10)`|
|@Trocknersymbole.Trocknen(10)|_Trocknen_|`@Trocknersymbole.Trocknen(10)`|
|@Trocknersymbole.Trommeltrocknen_niedrige_Temperatur(10)|_Trommeltrocknen niedrige Temperatur_|`@Trocknersymbole.Trommeltrocknen_niedrige_Temperatur(10)`|
|@Trocknersymbole.Trommeltrocknen_normale_Temperatur(10)|_Trommeltrocknen normale Temperatur_|`@Trocknersymbole.Trommeltrocknen_normale_Temperatur(10)`|
|@Trocknersymbole.Trommeltrocknen(10)|_Trommeltrocknen_|`@Trocknersymbole.Trommeltrocknen(10)`|

### Waschsymbole


© by GINETEX GERMANY, www.ginetex.de


mit `@Waschsymbole.licence` kann der Text ausgegeben werden.
<!-- START OF TABLE -->
|Bild|Name|Befehl|
|---|---|---|
|@Waschsymbole.Handwaesche(10)|_Handwaesche_|`@Waschsymbole.Handwaesche(10)`|
|@Waschsymbole.Nicht_waschen(10)|_Nicht waschen_|`@Waschsymbole.Nicht_waschen(10)`|
|@Waschsymbole.waschen_bei_30_grad_schonend(10)|_waschen bei 30 grad schonend_|`@Waschsymbole.waschen_bei_30_grad_schonend(10)`|
|@Waschsymbole.waschen_bei_30_grad_sehr_schonend(10)|_waschen bei 30 grad sehr schonend_|`@Waschsymbole.waschen_bei_30_grad_sehr_schonend(10)`|
|@Waschsymbole.waschen_bei_30_grad(10)|_waschen bei 30 grad_|`@Waschsymbole.waschen_bei_30_grad(10)`|