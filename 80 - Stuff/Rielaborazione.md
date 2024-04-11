---
banner: "![[banner per Rielaborazione.jpg]]"
banner_y: 0.916
banner_lock: true
banner_icon: 🟧
cssclasses:
  - academia
---
*The notes now have sense, but they're… quite ugly still*.
***
```dataview
table
  corso AS "Corso",
  mastery AS "Mastery",
  file.cday AS "Creato",
  abstract AS "Abstract"
from #📄note/🟧rielaborazione
where file.name!= "render"
where file.folder!= "90 - Templates/Corsi Uni"
sort data ASC
```
