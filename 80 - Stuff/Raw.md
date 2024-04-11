---
banner_icon: 🟥
banner: "https://r4.wallpaperflare.com/wallpaper/967/89/86/minimalism-code-quote-text-wallpaper-e7793a7b66fa05e57c0d783058177943.jpg"
banner_y: 0.464
banner_lock: true
cssclasses:
  - academia
---
*Just raw notes, no fancy stuff*.
***
```dataview
table
  corso AS "Corso",
  mastery AS "Mastery",
  file.cday AS "Creato",
  file.mtime AS "Modifica"
from #📄note/🟥raw
where file.name!= "render"
where file.folder!= "90 - Templates/Corsi Uni"
sort data ASC
```

***