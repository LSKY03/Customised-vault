---
banner: "![[banner per Revisione.jpg]]"
banner_y: 0.584
banner_lock: true
banner_icon: 🟨
cssclasses:
  - academia
---
*Last check and let's make 'em beutiful*
***
```dataview
table
  corso AS "Corso",
  mastery AS "Mastery",
  file.cday AS "Creato",
  abstract AS "Abstract"
from #📄note/🟨revisione
where file.name!= "render"
where file.folder!= "90 - Templates/Corsi Uni"
where "corso"= "psicologia dinamica" OR "psicometria" OR "psicologia dello sviluppo" OR "current debates in cognitive neuroscience"
sort data DESC
```

