# Academic-Conference-Ontology
## Project Description
This project focuses on the development of an ontology designed to manage and organize data related to academic conferences. It provides a structured framework for representing entities such as research papers, authors, conference sessions, and university affiliations. The ontology was developed using the *OntoClean* methodology to ensure semantic rigor and logical consistency.

## Purpose and Scope
The primary goal of this ontology is to facilitate the querying of conference schedules, tracking paper authorship, and managing participant roles (Reviewers, Speakers, Authors). The scope includes:
- *People:* Authors, Reviewers, and Session Chairs.
- *Documents:* Academic Papers and their metadata.
- *Events:* Sessions, Tracks, and Organizing Institutions.

## Key Competency Questions (CQ)
The ontology is designed to answer the following questions:
1. Which papers are assigned to which session?
2. Who are the authors of a specific research paper?
3. Which research topic does a specific track focus on?
4. What is the scheduled date and time for a given session?
5. Which university is an author affiliated with?

## Technical Details
- *Prefix:* http://www.semanticweb.org/furka/ontologies/2026/3/academic-conference
- *Format:* OWL/XML
- *Tools Used:* Protégé 5.x, HermiT Reasoner.
- *Logic:* Includes Inverse Properties, Disjoint Classes, and Domain/Range Restrictions.

## How to View
1. Download the Academic_Conference_Ontology.owl file.
2. Open *Protégé*.
3. Go to File > Open and select the downloaded file.
4. Start the *HermiT Reasoner* to view inferred relationships.
