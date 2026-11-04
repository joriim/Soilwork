# Soilwork

**Soilwork is an interactive reading companion that explains the fundamental laws and processes behind soil, environmental and agricultural science, and tests the common misconceptions about them.**

It runs as a single static web page (`index.html`) with no build step and no server.

## What it contains

| Part | Content |
|---|---|
| Library | 103 entries in six fields: physics (16), chemistry (20), soil science (21), environment (11), research methods (17) and agricultural economics (18). 30 are full articles with origin, intuition, skim/full mathematics, field relevance, limits and misconceptions, and further reading; the rest are short entries. |
| Concept map | Force-directed map of how the laws depend on each other. |
| Reading paths | 14 curated sequences, e.g. *Fixing nitrogen: nodules and factories*, *The nitrogen cycle, process by process*, *From plot trial to carbon flux*, *Contaminated land (PIMA)*. |
| Briefs | One-card summaries of each entry, by path or for the whole library. |
| Quiz | 216 multiple-choice questions, each built around a common misconception. Answer order is shuffled on every showing. A wrong answer explains the misconception and links to the exact section to reread. 105 questions cite a textbook page. |

Reading progress and the reread list are stored only in the reader's own browser (`localStorage`).

## Use

Open `index.html` in a browser, or publish the repository with GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder). Fonts load from Google Fonts; everything else is in the one file.

Deep links: `index.html#quiz`, `#map`, `#paths`, `#brief`, or an entry id such as `#n2o`, `#darcy`, `#gwp`.

## Sources

Page-referenced questions and field notes draw on four textbooks and one Finnish handbook, listed in [SOURCES.md](SOURCES.md). The books are cited, not reproduced: all text in Soilwork is newly written.

## Context

<!-- TODO (author): name the SEAMK RDI project or task this work belongs to, e.g. "Developed as part of the ... project at Seinäjoki University of Applied Sciences (SEAMK)". -->
Developed by Miiro Jääskeläinen in soil and environmental science RDI work at Seinäjoki University of Applied Sciences (SEAMK).

## Author's contribution

<!-- TODO (author): review and complete this section so that it describes your own contribution accurately. -->
Soilwork was produced with AI assistance (Claude, Anthropic). The author's contribution:

- defined the purpose, scope and structure of the companion;
- chose the laws, processes and reading paths, including the methods, economics, contaminated-land, nitrogen-cycle and nitrogen-fixation sections;
- supplied the source literature and directed which sources each section draws on;
- directed and reviewed the content in iterative revision rounds;
- *(add: subject-matter checking of articles and quiz answers, corrections made, testing with students or colleagues, etc.)*

AI tools drafted the text, quiz items and code under the author's direction.

## How to cite

See [CITATION.cff](CITATION.cff), or use the "Cite this repository" button on GitHub. After the first Zenodo release, cite the DOI shown on the Zenodo record.

## Licence

Text and code: [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).

---

**Suomeksi:** Soilwork on selaimessa toimiva lukuopas maaperä-, ympäristö- ja maataloustieteen peruslakeihin ja -prosesseihin. Siinä on 103 artikkelia, käsitekartta, 14 lukupolkua, tiivistelmäkortit ja 216 kysymyksen tietovisa yleisistä väärinkäsityksistä.
