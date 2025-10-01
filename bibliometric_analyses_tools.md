# Research and Analysis Tools

This document lists several research and bibliographic analysis tools used, along with notes on their limitations and functionalities.

## Research and Analysis Tools – Evaluation

Remembering that the requirements for the tool to be used to perform the Literature Review were:
- **Inferred information** – comprehend contextual information and not limited to word comparison;
- **Large scale** - capacity to work with hundreds or even thousands of documents;
- **PDF access** – possibility to access the full texts of the manuscript and not just keywords, authors, title and abstract;
- **Personalized query** – the system must allow searching for the exact information intended from the articles.
- **Open-source** – preference for open-source software solutions was given.

Considering these requirements, the following table was developed:

| Research and Analysis Tool | Inferred information | Large scale | PDF access | Personalized query | Open-source |
|----------------------------|----------------------|-------------|------------|--------------------|-------------|
| **Elicit**                | ✅ Yes – contextual inference via AI | ⚠️ Limited | ❌ No | ✅ Yes | ❌ No |
| **VOSviewer**             | ❌ No – citation network only | ✅ Yes | ❌ No | ⚠️ Limited | ✅ Yes |
| **CiteSpace**             | ❌ No – bibliometric visualization | ✅ Yes | ❌ No | ⚠️ Limited | ✅ Yes |
| **Scispace**              | ✅ Yes – extracts from PDFs | ⚠️ Limited | ✅ Yes | ✅ Yes | ❌ No |
| **Research Rabbit**       | ⚠️ Limited – strong in relations, weak in search | ⚠️ Limited | ❌ No | ❌ No | ❌ No |
| **Copilot (Microsoft)**   | ✅ Yes (AI-based) | ❌ No | ❌ No | ⚠️ Limited | ❌ No |
| **ChatGPT**               | ✅ Yes (contextual understanding) | ✅ Yes (depends on data input) | ⚠️ With plugins/API | ✅ Yes | ❌ No |
| **KNIME**                 | ✅ Possible with extensions | ✅ Yes | ⚠️ Needs configuration | ✅ Yes | ✅ Yes |
| **SCITE**                 | ✅ Yes – citation context analysis | ⚠️ Limited | ❌ No | ⚠️ Limited | ❌ No |
| **Publish or Perish**     | ❌ No – relies on Google Scholar metadata | ⚠️ Limited | ❌ No | ❌ No | ❌ No |
| **Semantic Scholar API**  | ✅ Yes – NLP powered | ✅ Yes | ⚠️ Metadata only | ✅ Yes | ✅ Yes |
| **Scholarcy**             | ✅ Yes – summarization | ❌ No | ✅ Yes (per paper) | ❌ No | ❌ No |
| **Lens.org**              | ⚠️ Limited | ✅ Yes | ❌ No | ✅ Yes | ✅ Yes |
| **Consensus**             | ✅ Yes – AI summarization | ⚠️ Limited | ❌ No | ⚠️ Limited | ❌ No |
| **Perplexity**            | ✅ Yes – AI search | ✅ Yes | ❌ No | ❌ No | ❌ No |
| **NLP with Python (.pdf/.bib)** | ✅ Yes – fully customizable | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes |

---

✅ = Meets requirement  
⚠️ = Partial / Limited  
❌ = Does not meet requirement  
TBD = To be defined (needs further analysis)  

---

## 🔧 Research and Analysis Tools

- **Elicit** – very limited number of possible articles for review  
- **VOSviewer** – requires download  
- **CiteSpace** – requires download  
- **Scispace** – searches or extracts information from PDFs  
- **Research Rabbit** – excellent for mapping relations between works, but still missing integration with all files; strong in relationships, weak in thematic search  
- **Copilot (Microsoft)** – does not accept `.bib` files  
- **ChatGPT** – supports textual analysis  
- **KNIME** – integrates unstructured information; requires further study  
- **SCITE** – contextual citation analysis  
- **Publish or Perish** – integrates Google Scholar + NLP  
- **Semantic Scholar API** – programmatic access to papers  
- **Scholarcy** – analyzes one paper at a time  
- **Lens.org** – limited analysis  
- **Consensus** – emerging tool for article summarization  
- **Perplexity** – AI-assisted search  
- **NLP with Python (via PDF and .bib)** – mixed results  

---

## 📊 Extraction and Analysis Results

### 🔹 Elicit
- **Input space:** local (18) vs global (7) → **28% vs 72%**  
- **Physical nature:** kinematic (18) vs dynamic (4) → **82% vs 18%**  
- **Generation space:** joint space (13) vs operational space (7) → **65% vs 35%**  
- **Obstacle avoidance:** yes (3) vs no (14) vs maybe (1) → ⚠️ inconsistencies  
- **Testing:** simulation (9) vs humanoid robots (6) vs robotic manipulators (13) → **32% vs 21% vs 46%**

---

### 🔹 Scispace
- **Input space:** online (4) vs offline (1) → **80% vs 20%**  
- **Physical nature:** kinematic (7) vs dynamic (5) → **58% vs 42%**  
- **Generation space:** joint space (5) vs operational space (3) → **62.5% vs 37.5%**  
- **Obstacle avoidance:** yes (6)  
- **Testing:** simulation (6) vs humanoid robots (5) vs robotic manipulators (7) → **33% vs 28% vs 39%**

---

### 🔹 Global Analysis
- **Input space:** online (80%) vs offline (20%)  
- **Physical nature:** kinematic (77.78%) vs dynamic (22.22%)  
- **Generation space:** operational (77.78%) vs joint (22.22%)  
- **Obstacle avoidance:** yes (94.44%) vs no (5.56%)  
- **Testing:** humanoid robots (44.44%) vs simulation (27.78%) vs robotic manipulators (27.78%)  

---
