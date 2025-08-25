<!--
author: Volker Göhler
version: 0.0.4
edit: true
comment: This repository is a collection of textile care signs for the DiAgnostiK Project
@import: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/makros.md
attribute: all images: © by GINETEX GERMANY, www.ginetex.de


-->

# Badges

![Github Makro-build action](https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/actions/workflows/github_workflows_update-makros.yml/badge.svg)

[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/refs/heads/main/README.md)

[![GitHub](https://img.shields.io/badge/Ansehen%20auf-GitHub-181717?logo=github)](https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/blob/main/README.md)

# DiAgnostiK Textilpflegesymbole

Repository für Textilpflegesymbole nach ISO 3758:2023.

Alle Bilder sind © by GINETEX GERMANY, [www.ginetex.de](www.ginetex.de)

- Link zur LiaScript [Bildhilfe](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#24)! 😃

Das  LiaScript Dokument muss mit einem Kommentar beginnen indem die Makro Datei eingefügt wird. Das kann auch in dieser Datei beobachtet werden.

```markdown
<!--
@import: https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/blob/main/makros.md?raw=true
-->
```

## Beispiel

Alle Beispiele funktionieren nur mit LiaScript und nicht hier im Github! Bitte obigen Link zu Kurs oder Live Editor nutzen.

### einfach mit Makro:

> `@Waschsymbole.Handwaesche(10)`

@Waschsymbole.Handwaesche(10)

- aber Achtung Deutsche Umlaute sind ausgeschrieben! (ä=ae usw.)

### schwieriger direkt als markdown Bild

- funktioniert auch außerhalb von LiaScript!

```md
![Beispielzeichen](https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/blob/main/Trocknersymbole/Trocknen.jpg?raw=true)<!-- style="height: 10rem;" -->
```

![Beispielzeichen](https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/blob/main/img/Waschsymbole/Handwaesche-max-40-grad.png?raw=true)<!-- style="height: 10rem;" -->

### Skalierung

Der Parameter (die Zahl in den runden Klammern) steuert die Größe in Zeilenhöhe des Textes.

> `@Reinigungssymbole.license`

@Reinigungssymbole.license

> `@Reinigungssymbole.Professionelle_Nassreinigung_sehr_schonend(10)`
@Reinigungssymbole.Professionelle_Nassreinigung_sehr_schonend(10)

> `@Reinigungssymbole.Professionelle_Nassreinigung_sehr_schonend(5)`
@Reinigungssymbole.Professionelle_Nassreinigung_sehr_schonend(5)

> `@Reinigungssymbole.Professionelle_Nassreinigung_sehr_schonend(1)`
@Reinigungssymbole.Professionelle_Nassreinigung_sehr_schonend(1)

## Bildermakros

Alle Bilder sind in dieser Datei abgebildet:

- [makros.md](https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/blob/main/makros.md)

Zum anzeigen bitte folgenden LiaScript Link benutzen:

[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://github.com/Ifi-DiAgnostiK-Project/Textilpflegesymbole/blob/main/makros.md?raw=true)
