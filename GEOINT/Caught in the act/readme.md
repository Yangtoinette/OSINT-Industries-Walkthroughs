


## La Dérive — OSINTOPIA | Géolocalisation | Medium

**Énoncé :** 

<div align="left">
  Challenge:
  
  <p>A photo has been recovered during an investigation.</p>
  
  <p>Your objective is to determine:
  <ul>
    <li>The name of the university where the photo was taken</li>
    <li>The city in which it is located</li>
  </ul>
  
  <p>Flag format: OSINT{"university_name_city"}</p>
  <p>Example: OSINT{"harvard_university_cambridge"}</p>
  
  <p>Good luck.</p>
</div>

**Outils :** `exiftool` · `Yandex Images` · `Google Street View` · `Wayback Machine`

<details>
<summary>Résolution (spoiler)</summary>

**[01] Métadonnées EXIF** — Aucun GPS, photo réexportée Photoshop.

**[02] Reverse image search** — Yandex → Barcelone, Espagne.

**[03] Architecture + Street View** — Barrio Gràcia → Carrer de Verdi.

**[04] Datation** — Wayback Machine → première capture 2019-03-14.

</details>

**Flag :** `OSINTOPIA{Carrer_de_Verdi_2019}`
