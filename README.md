# Digital Publications Landing Page

## Proof of concept prototype
Open notebook link: [https://github.com/NFDI4Culture/digital-publications-landing-page](https://github.com/NFDI4Culture/digital-publications-landing-page)
July 2023, Digital Publications and Data Working Group (DPD), NFDI4Culture

## Description and objectives
**Landing Page (aka Access URL):** A landing page for a publication that contains information and link to all of the publication editions/releases and incremental versions, output formats, and sources, or other significant resources.This information needs to be human readable and machine readable.
Currently most publications, publishers, and repositories do not appear to carry such link information in a satisfactory or comprehensive way. The working group considered landing pages to be an overlooked and important issue that needs resolving to enable wider adoption by the community.
The W3C does approach the idea of landing pages using the concept of *packaging*, as for example with [Packaged Web Publications](https://www.w3.org/TR/pwpub/) and [Lightweight Packaging Format (LPF)](https://www.w3.org/TR/lpf/). Additionally in software there is the engineering model of *[package management](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Package_management)*.
**Objectives:** The objectives are to:
1. Keep a track of all relevant versions and resources of a publication;
2. Make sure information is portable and that each output or source has the necessary information about all other resources, and;
3. To make a sustainable and general system for landing pages.
**The project will make a proof-of concept prototype with the selected use cases, using linked open data in Wikidata and Wikibase, with an output rendered from a SPARQL query.**

## Use cases
There are two use case publications.
* Use case #1: A multi-format research survey report made by a working group and published as multi-format on GitHub.
*Digital Publications in Culture: Examples and Key Features – Survey Results from the NFDI4Culture Community:* [https://tibhannover.github.io/digital-publications-in-culture-survey-results/](https://tibhannover.github.io/digital-publications-in-culture-survey-results/)
* Use case #2: A multi-modal PhD Thesis which is made of a conventional open access paper and a data visualisation made with Neo4j.
CITADEL: Computational Investigation of the Topographical and Architectural Designs in an Evolving Landscape: [https://www.wikidata.org/wiki/Q116701915](https://www.wikidata.org/wiki/Q116701915)

## Work program
* Desk research: Data models, existing examples for other publications, community consultation.
* Create schematic diagram of data model for two use cases in [https://app.diagrams.net/](https://app.diagrams.net/)
* Model the two use case publications in Wikidata:
 * Digital Publications in Culture: Examples and Key Features – Survey Results from the NFDI4Culture Community[ https://www.wikidata.org/wiki/Q114123116](https://www.wikidata.org/wiki/Q114123116)
 * CITADEL: Computational Investigation of the Topographical and Architectural Designs in an Evolving Landscape[ https://www.wikidata.org/wiki/Q116701915](https://www.wikidata.org/wiki/Q116701915)
* Find assistance to help create SPARQL query to output human readable version and machine version. Render using Jupyter Notebook and Quarto.
* Consult the community and share outstanding questions.

## Literature and link
Article Source: [Identifiers for the 21st century: How to design, provision, and reuse persistent identifiers to maximize utility and impact of life science data](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2001414)
McMurry JA, Juty N, Blomberg N, Burdett T, Conlin T, et al. (2017) Identifiers for the 21st century: How to design, provision, and reuse persistent identifiers to maximize utility and impact of life science data. PLOS Biology 15(6): e2001414. [https://doi.org/10.1371/journal.pbio.2001414](https://doi.org/10.1371/journal.pbio.2001414)

## Working information
Ticket link: [https://tickets.nfdi4culture.de/projects/digital-preservation-services/work_packages/5681/activity](https://tickets.nfdi4culture.de/projects/digital-preservation-services/work_packages/5681/activity)

---

End
