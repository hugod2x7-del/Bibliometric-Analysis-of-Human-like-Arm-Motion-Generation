
---

## 📊 Contents

- **Data**: Full list of articles used in the study, available in CSV and BibTeX.  
- **Results**: Tables with aggregated data and bibliometric indicators.   

---

## ❓ How to Use

1. Clone this repository or download it as a ZIP.  
2. Import `list_of_articles.bib` into your reference manager (Zotero, Mendeley, EndNote).  

---

## 🔍 Research 
- The article collection was obtained considering the following criteria

  | **E#** | **Criteria**   | **Statement**                                                                 |
  |--------|----------------|-------------------------------------------------------------------------------|
  | E1     | Availability   | Full text of the papers not available in digital libraries                    |
  | E2     | Language       | Full text of the papers not published in English                              |
  | E3     | Year           | Papers not included in the year range of [2006–2024]                          |
  | E4     | Scope          | Papers that do not focus on humanoid robots or related motion planning/generation |
  | E5     | Topic Relevance| Papers that do not address arm/upper-limb motion, legibility, predictability, or human-like trajectories |
  | E6     | Source Type    | Papers not published in peer-reviewed journals or conference proceedings      |

- The results presented are from 4 different libraries with the following search
  | **Library** | **Search Expression** |
  |-------------|-----------------------|
  | IEEE explore |(((arm OR upper-limb) AND (human-like OR legible OR predictable) AND (motion OR movement OR trajectory)) AND (humanoid OR robot) AND (planning OR generation) ) With the following filters: Conferences,Journals and 2006-2025|
  | Scopus |( TITLE-ABS-KEY ( arm ) OR TITLE-ABS-KEY ( upper-limb ) ) AND ( TITLE-ABS-KEY ( human-like ) OR TITLE-ABS-KEY ( legible ) OR TITLE-ABS-KEY ( predictable ) ) AND ( TITLE-ABS-KEY ( motion ) OR TITLE-ABS-KEY ( movement ) OR TITLE-ABS-KEY ( trajectory ) ) AND ( humanoid OR robot ) AND ( planning OR generation ) AND PUBYEAR > 2005 AND ( LIMIT-TO ( SRCTYPE , "p" ) OR LIMIT-TO ( SRCTYPE , "j" ) ) AND ( LIMIT-TO ( LANGUAGE , "English" ) )|
  | Web of Science| TS=(arm OR upper-limb) AND TS=(human-like OR legible OR predictable) AND TS=(motion OR movement OR trajectory) AND TS=(humanoid OR robot) AND TS=(planning OR generation) AND PY=(2006-2025) AND LA=(English) AND DT=(Article OR Proceedings Paper)|
  | ACM Digital Library| [[[Abstract: "arm"] OR [Abstract: "upper limb"]] AND [[Abstract: "human-like"] OR [Abstract: "legible"] OR [Abstract: "predictable"]] AND [[Abstract: "motion"] OR [Abstract: "movement"] OR [Abstract: "trajectory"]] AND [[Abstract: "humanoid"] OR [Abstract: "robot"]] AND [[Abstract: "planning"] OR [Abstract: "generation"]]] OR [[[Keywords: "arm"] OR [Keywords: "upper limb"]] AND [[Keywords: "human-like"] OR [Keywords: "legible"] OR [Keywords: "predictable"]] AND [[Keywords: "motion"] OR [Keywords: "movement"] OR [Keywords: "trajectory"]] AND [[Keywords: "humanoid"] OR [Keywords: "robot"]] AND [[Keywords: "planning"] OR [Keywords: "generation"]]] OR [[[Title: "arm"] OR [Title: "upper limb"]] AND [[Title: "human-like"] OR [Title: "legible"] OR [Title: "predictable"]] AND [[Title: "motion"] OR [Title: "movement"] OR [Title: "trajectory"]] AND [[Title: "humanoid"] OR [Title: "robot"]] AND [[Title: "planning"] OR [Title: "generation"]]] AND [E-Publication Date: (01/01/2006 TO 01/31/2025)] |

## 📖 Citation

If you use this dataset, please cite the original article:

> Authors. *"[An Intelligent Framework for Bibliometric Analysis and Literature Review of Human-like Arm Motion Generation]"*. Revista, Ano. DOI: [link]

Additionally, you may cite this repository as:

> [Authors]. *Bibliometric-Analysis-of-Human-like-Arm-Motion-Generation*. GitHub repository. Available at: [https://github.com/hugod2x7-del/Bibliometric-Analysis-of-Human-like-Arm-Motion-Generation/tree/main]

---

## 📝 License

This repository and its contents are licensed under the  
**Creative Commons Attribution 4.0 International License (CC-BY-4.0)**.  

This means you are free to:  
- Share — copy and redistribute the material in any medium or format.  
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.  

As long as you give appropriate credit to the authors.  

For details, see the [LICENSE](LICENSE) file or visit:  
https://creativecommons.org/licenses/by/4.0/
