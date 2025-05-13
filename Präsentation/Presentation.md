---
marp : true
theme: default

---
<!-- paginate : skip-->

# <CENTER>Zwischenpräsentation</CENTER>
## <CENTER>Stagelight</CENTER>
<CENTER>Julian Burner, Kevin Forst, Maxi Endl, Maxim Udod</CENTER>

---
<!-- footer : "Stagelight - Zwischenpräsentation" -->
<!--paginate : true-->

# <CENTER>Gliederung</CENTER>

- Motivation und Ideenfindung
- Konzeptuelle Umsetzung
- Technische Umsetzung
- Momentaner Stand
- Fazit und Ausblick

---

# <CENTER>Motivation und Ideenfindung</CENTER>

- Grundidee von einem Kommilitonen aus dem Studiengang Medientechnik
- Bedarf an kostengünstiger Scheinwerferausichtungslösung
- Einsatz bei Doschauher-TV etc.

---

# <CENTER>Bezug zur Nachhaltigkeit</CENTER>

SDGs:
- [Goal 9](https://sdgs.un.org/goals/goal9):
  > Develop [...] infrastructure [...] with a focus on affordable and equitable access for all.
- [Goal 12](https://sdgs.un.org/goals/goal12):
  > Substantially reduce waste generation through prevention, reduction, recycling and reuse.

---

# <CENTER>Konzeptuelle Umsetzung</CENTER>

- Schwenkbare Scheinwerfer
- Am mittleren Scheinwerfer montierte Kamera
- Kabellose Übertragung der Bewegtbilder an PC
- Python-Programm:
  - Objekterkennung
  - Objektauswahl durch Nutzereingabe
  - Verfolgung des Objekts im Videostream
  - Automatische Ausrichtung der Scheinwerfer

---

# <CENTER>Technische Umsetzung</CENTER>

- Scheinwerfer: T1 Profile
- Kamera: ?
- Software:
  - Python
  - OpenCV für Videoeingabe
  - YOLO-Modell für Objekterkennung

![bg right](https://cdn.aws.robe.cz/v1/image/resize/422fbc138a8a68463837f9885cdfbffbc5076d0a?width=452&height=485&fit=cover&withoutEnlargement=false)

---

# <CENTER>Momentaner Stand</CENTER>

- Zugriff auf Hardware als limitierender Faktor
- Lego Mindstorms als Testplattform?
- Software:
  ![height:350px](./assets/example-video-thumbnail.png)

---

# <CENTER>Fazit und Ausblick</CENTER>

Schwerer als gedacht um geeignete Software zu finden/entwickeln um Objekte/Personen zu verfolgen.

---

# <CENTER>GitHub Repo</CENTER>
<center>

![Github Repository](./assets/repo-qr-code.png)
[https://github.com/exiidor/Stagelight](https://github.com/exiidor/Stagelight)
</center>