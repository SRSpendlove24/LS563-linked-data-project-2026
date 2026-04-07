# LS563-linked-data-project-2026
**About:** This is my linked data project for LS563. It contains data about the actor Cary Grant.

**Description:** This dataset contains data about the 73 films that the British-American actor Cary Grant appeared in over the course of his very successful career. There is data about the directors, genres, studios, stars, creation dates, names, length, and IMDB (International Movie Database) rating of each film. 

**Ontologies and controlled Vocabularies Used:** I used shcema.org for my controlled vocabulary terms. I reconcilled my data using Wikidata.

**Linking Strategy:** Each movie in this dataset has the actor Cary Grant in it. I used that list as a starting point, then linked data from the central point of each movie outwards into individual data for each film. I used URI's for "star", "director", "studio", "genre", and "IMDB rating" since these have wikidata entries. For "duration", "title" and "year", I made these literals. I did this because I wanted to represent the raw text of each of these. Each of these links from the central "movie" point. The only link that doesen't is the literal "decimal", which linkes from "IMDB Rating". 

**Sample Triples:** _Arsenic and Old Lace_ → was directed by → Frank Capra, _Penny Serenade_ → has an IMDB Rating → of 7.1
