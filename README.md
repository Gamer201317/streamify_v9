# streamify_v9

Streamify — Handleiding
Hoe werkt het?
Je kiest één mediamap op je iPad. Streamify leest alle bestanden daarin en toont ze netjes als films, series en collecties. De map staat gewoon in de Bestanden-app — op je iPad zelf, op een USB-stick of externe harde schijf.

Mappenstructuur
Je mediamap heeft drie vaste hoofdmappen:

📁 Mijn Media
├── 📁 Movies
├── 📁 Series
└── 📁 Collections

Tip: De map mag ook "Films" heten in plaats van "Movies" — beide werken.

🎬 Films (Movies)
Zet losse films direct in de map Movies/.

📁 Movies
├── Inception.mp4
├── Inception.jpg          ← cover (zelfde naam als de film)
├── Interstellar.mp4
├── Interstellar.jpg
├── The Dark Knight.mkv
└── The Dark Knight.png

Regels:

Het coverbeeldje heeft dezelfde naam als de film (alleen de extensie verschilt)
Ondersteunde videoformaten: .mp4 .mkv .avi .mov .m4v .webm
Ondersteunde afbeeldingen: .jpg .jpeg .png .webp
📺 Series
Elke serie krijgt een eigen submap in Series/. Daarin staan de afleveringen.

📁 Series
├── 📁 Breaking Bad
│   ├── cover.jpg          ← seriecover (noem het altijd "cover")
│   ├── S01E01.mp4
│   ├── S01E02.mp4
│   ├── S02E01.mp4
│   └── S02E02.mp4
├── 📁 The Office
│   ├── cover.png
│   ├── S01E01 - Pilot.mp4
│   ├── S01E02 - Diversity Day.mp4
│   └── S02E01 - The Dundies.mp4
└── 📁 Stranger Things
    ├── cover.jpg
    ├── 1x01.mp4           ← dit formaat werkt ook
    ├── 1x02.mp4
    └── 2x01.mp4

Naamgeving afleveringen — dit werkt allemaal:

Bestandsnaam	Seizoen	Aflevering
S01E01.mp4	1	1
S02E05 - Titel.mp4	2	5
1x01.mp4	1	1
Episode 3.mp4	1	3
Regels:

Het coverbestand heet altijd cover.jpg (of .png, .webp)
Streamify groepeert afleveringen automatisch per seizoen
Bestanden worden gesorteerd op seizoen en afleveringsnummer
🗂️ Collecties (Collections)
Collecties zijn vrije groepen — voor documentaires, stand-up comedy, muziekconcerten, kinderfilms, etc.

📁 Collections
├── 📁 Marvel Films
│   ├── cover.jpg          ← collectiecover
│   ├── Iron Man.mp4
│   ├── Thor.mp4
│   └── The Avengers.mp4
├── 📁 Documentaires
│   ├── cover.jpg
│   ├── Planet Earth.mp4
│   └── Blue Planet.mp4
└── 📁 Kinderfilms
    ├── cover.jpg
    ├── Toy Story.mp4
    └── Finding Nemo.mp4

Regels:

Geen vaste naamgeving nodig — zet gewoon videobestanden in de map
Coverbestand noem je cover.jpg
Geen subsubmappen — alle video's staan direct in de collectiemap
Samenvatting covers
Type	Hoe heet het coverbestand?
Film	Zelfde naam als de film: Inception.jpg
Serie	cover.jpg in de seriesmap
Collectie	cover.jpg in de collectiemap
Geen cover? Streamify toont een oranje standaardafbeelding. Alles werkt gewoon, covers zijn optioneel.

De app opstarten
Open Streamify via je browser of beginscherm
Tik op "Tik hier om te starten"
Kies je mediamap (de map met daarin Movies, Series, Collections)
De bibliotheek laadt automatisch
Na een herstart van de app:

Tik op het ↺ vernieuw-icoon om je map opnieuw te laden
Of tik op + om een andere map te kiezen
Tips
Beste videoformaat voor iPad: .mp4 met H.264 of H.265 codec — die spelen altijd soepel af
MKV-bestanden: werken soms niet op Safari — converteer ze naar .mp4 als ze niet afspelen
Ondertitels: worden momenteel niet ondersteund — gebruik video's met ingebakken ondertitels
Mapnamen zijn niet hoofdlettergevoelig — movies, Movies en MOVIES werken allemaal
