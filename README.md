# Video-Stuff

> Un loc pentru tot ce ține de **video production**: idei, concepte, scenarii, planuri de filmare, resurse, workflow-uri și documentația proiectelor.

Acest repository centralizează procesul de la prima idee până la livrarea finală. Scopul este ca fiecare producție să pornească de la aceleași șabloane, să fie ușor de urmărit și să poată fi reluată sau predată altei persoane fără pierdere de context.

## Ce găsești aici

- **Pre-production:** brief-uri, concepte, research, scenarii, storyboard-uri și shot lists.
- **Production:** planuri de filmare, echipament, locații, checklist-uri și note de pe set.
- **Post-production:** structură de montaj, note de feedback, reguli pentru audio/color și preseturi documentate.
- **Assets & resources:** grafică, SFX, muzică și referințe *doar când există drepturi de folosire și distribuire*.
- **Deliverables:** specificații pentru export, thumbnails, subtitrări și linkuri către versiuni aprobate.

## Structura repository-ului

```text
Video-Stuff/
├── README.md
├── templates/
│   ├── concept-structura-video.md
│   └── concept-structura-video.docx
├── projects/
│   └── YYYY-MM-nume-proiect/
│       ├── 00-brief/
│       ├── 01-pre-production/
│       ├── 02-production/
│       ├── 03-post-production/
│       └── 04-delivery/
└── assets/
    └── README.md
```

Directoarele din `projects/YYYY-MM-nume-proiect/` sunt un **exemplu de structură**; se creează separat pentru fiecare proiect. Directoarele goale nu sunt urmărite automat de Git.

## Cum începi un proiect nou

1. Creează `projects/YYYY-MM-nume-proiect/` și subfolderele necesare.
2. Copiază `templates/concept-structura-video.md` în `01-pre-production/concept.md` sau folosește varianta `.docx`.
3. Completează brief-ul, publicul, obiectivul, secvențele video și checklist-ul de filmare.
4. Actualizează documentele pe măsură ce proiectul trece prin filmare, montaj și review.
5. Păstrează în `04-delivery/` specificațiile, notele de livrare și linkul către fișierele finale.

**Workflow recomandat:** `Idea → Concept → Script → Shot list → Shooting → Rough cut → Review → Final cut → Delivery`.

## Convenții de denumire

Folosim nume clare, fără spații, diacritice sau variante de tip `final_final_2`.

```text
2026-10-nume-proiect/
2026-10-22_nume-proiect_shot-list_v01.md
nume-proiect_script_v02.md
nume-proiect_youtube_16x9_v03.mp4
nume-proiect_reels_9x16_v01.mp4
```

Crește versiunea la modificări relevante (`v01`, `v02`, `v03`). Marchează explicit fișierul aprobat în documentele proiectului, nu doar în numele exportului.

## Ce păstrăm în Git și ce nu

**În Git:** Markdown, documentație, liste de cadre, scenarii, setări text, grafică ușoară și fișiere de proiect suficient de mici pentru versionare.

**În storage extern:** footage RAW, proxies, cache, renderuri intermediare, exporturi video mari și biblioteci audio voluminoase. În repo păstrăm calea sau linkul către acestea, plus cine are acces.

Dacă un asset binar trebuie urmărit în Git, folosește [Git LFS](https://git-lfs.com/) și verifică limitele de stocare ale proiectului. **Nu încărca parole, date personale, material confidențial sau conținut fără drepturi de distribuire.**

## Review și colaborare

- Deschide un *Issue* pentru propuneri, taskuri sau probleme identificate.
- Folosește *Pull Requests* pentru modificări de șabloane, ghiduri și resurse comune.
- În feedback, indică **versiunea**, **timecode-ul**, **problema** și **modificarea propusă**.
- Înainte de livrare, verifică imaginea, sunetul, subtitrările, brandingul și formatul pentru platforma țintă.

## Templates

| Fișier | Pentru ce este |
| --- | --- |
| [`templates/concept-structura-video.md`](templates/concept-structura-video.md) | Șablon ușor de editat direct în GitHub: structură pe secvențe, replici, cadre și checklist. |
| [`templates/concept-structura-video.docx`](templates/concept-structura-video.docx) | Aceeași structură într-un document Word formatat pentru lucru și distribuire. |


---
