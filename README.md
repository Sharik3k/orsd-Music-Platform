# Spotify Domain Ontology

## Project Overview
This repository contains the initial development of a domain ontology for a music streaming platform, inspired by Spotify. This project is developed as part of the **Knowledge Engineering and Ontologies** course.

## Purpose & Scope
* **Purpose:** To develop an ontology that models the relationships between audio content, user behavior, and metadata within a music streaming ecosystem.
* **Scope:** The ontology covers the structure of music catalogs (artists, albums, tracks), user entities (profiles, playlists), and genre classifications. It explicitly excludes financial aspects (royalties, subscription billing) and copyright management.

## Repository Structure
* `Music_Platform_ontology.owl` — The core ontology file developed in Protégé (OWL/RDF format) containing classes, properties, and initial instances.
* `orsd-Music_Platform.docx` — The Ontology Requirements Specification Document (ORSD) outlining design decisions, intended uses, and constraints.

## Key Concepts (Core Classes)
The initial model includes the following hierarchy:
* **Person:** `Artist`, `User`
* **AudioContent:** `Track`, `PodcastEpisode`
* **Collection:** `Album`, `Playlist`
* **Metadata:** `Genre`

## Competency Questions
The ontology is designed to answer the following functional requirements:
1. What tracks are included in album X?
2. Which artists are featured in user playlist Y?
3. What genre does artist Z belong to?
4. Which users are following artist Z?
5. When was track X released?

## Team Members
* Vladyslav Senkiv
* Oleksii Rak
* Illia Bredikhin
