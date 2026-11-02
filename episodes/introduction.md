---
title: "What next after specimen digitisation?"
teaching: 10 # teaching time in minutes
exercises: 5 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions 

- What information have we mobilised through specimen digitisation?
- Where are specimen records available?
- What evidence do they provide? 

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Discuss data mobilised through specimen digitisation
- Consider how different organisations may standardise their specimen data

::::::::::::::::::::::::::::::::::::::::::::::::

## Context

In our previous two sessions, we looked at:

- OpenRefine for improving data quality
    - Cleaning, standardising and preparing specimen data.
- R for analysing data at scale
    - Exploring, summarising and visualising specimen data.

In this session we will look at connecting specimen data: discovering relationships 
between specimens and reconstructing the collecting activities behind them, and what 
collections they have been accessioned into.

## Introduction

### Specimen digitisation

Herbarium specimen digitisation has generated large numbers of standardised 
specimen records and images, shared through institutional portals and aggregated 
into repositories like GBIF. 

### Specimens as evidence

Specimen records are often described as essential evidence - *what* / *where* / *when*.
Further investigation into how specimens were collected can uncover *who* collected 
(and identified) them, and *why* they were collected (eg to document a habitat or 
specific geographic location, or to expand our understanding of a particular 
taxonomic group).

### Data standardisation

Digitisation (and data aggregation) processes have taken care to standardise 
scientific names for specimens, but there are other fields commonly used for searching 
that are more variable in format, especially when records are searched in an aggregator, 
across specimens from different institutions.

| Attribute  | Field   | Level of completeness |
|---|---|---|
| what  | scientificName  |   |
| where  | countryCode, decimalLatitude/decimalLongitude  | 13% Kew specimens have coordinates  |
| when  | eventDate  |   |
| who  | recordedBy  |   |
| why  | field notebooks / collecting trip documentation  |   |
 

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: What kind of issues might you encounter when searching across specimen data from multiple institutions?

Review the table above and discuss with your neighbour for a couple of minutes.

:::::::::::::::::::::::: solution 

Report back to the whole group.

:::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: keypoints 

- Specimen records provide rich evidence.
- They have variable levels of information - because of data availability, or the level of information digitised.
- Post digitisation processes (e.g. georeferencing) can make records more usable.

::::::::::::::::::::::::::::::::::::::::::::::::

