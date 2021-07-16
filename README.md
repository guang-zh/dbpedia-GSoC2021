# dbpedia-GSoC2021
Google Summer of Code 2021 DBpedia Healthcare Platform. Project link: [https://github.com/dbpedia/healthcare-platform](https://github.com/dbpedia/healthcare-platform)

## Proposal
[Proposal for Healthcare Platform](https://docs.google.com/document/d/1kGc_-2c9FV_pjw5Y0rD3VW8jecGz4Q5MlsqZKiIYpZ8/edit#)

## COVID Mapping
[COVID-Mapping](https://drive.google.com/file/d/148L6tIGYblEgEZtLZ-LThCvaYY_jla29/view?usp=sharing)

## DBpedia Resources
- [DBpedia Web](https://www.dbpedia.org/)
- [Github Repo](https://github.com/dbpedia)
- [Get familiar with DBpedia Sparql databus](https://github.com/dbpedia/virtuoso-sparql-endpoint-quickstart)
- [GSoC 2020 Dashboard](https://github.com/dbpedia/gsoc-2020-dashboard)

## Healthplatform Resources
- [CORD-19: The Covid-19 Open Research Dataset](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7251955/)
- [Analyse and compare recency/correctness of Wikidata to recency/correctness of Wikipedia/DBpedia](https://svn.aksw.org/papers/2020/qurator_gfs/public.pdf)
- [SPARQL wikidata](https://www.wikidata.org/wiki/Wikidata:SPARQL_tutorial)
- [SPARQL w3](https://www.w3.org/TR/sparql11-query/)


## Proposed frameworks:
- Python Django (backend operations)
- Postgresql (database for CORD-19 dataset)
- SPARQL and Owl (query searching)
- Docker and Docker-compose (deployment)

## Meetings and Resources
June 15th 2021:
- [Sparql tool: TARQL](https://tarql.github.io/)
- [RDF turtle](https://www.w3.org/TR/turtle/)
- [Paper for Wikipedia and Wikidata](https://svn.aksw.org/papers/2020/qurator_gfs/public.pdf)
- [CORD-19 RDF dataset release](https://www.rd-alliance.org/group/rda-covid19/post/first-release-cord-19-named-entities-kg-rdf-dataset-named-entities-identified)
- [CORD-19 Dataset](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7251955/)
- [Sparql Practice](https://yasgui.triply.cc/)
- [Sparql query language](https://www.w3.org/TR/sparql11-query/)
- [Learn Sparql: Stardog](https://www.stardog.com/tutorials/sparql/)
- [RDF literals](https://www.w3.org/TR/turtle/#literals)
- [RDF primer](https://www.w3.org/TR/rdf11-primer/)
- [QA platform example](https://www.qanswer.eu/#try)
- [Spiral Model](https://en.wikipedia.org/wiki/Spiral_model)

Updated goals:
- Community Release Extension for COVID-19 HEALTHCARE
- Deploy a (DBpedia interlinked) healthcare dataset on the DBpedia Databus


If times allow: 
- Create a Dashboard
- Healthcare QA using this dataset
- demo QA using SPARQL


June 23rd 2021 meeting
- [dbpedia ontology Disease](https://dbpedia.org/ontology/Disease)
- [JSON2RDF Maven Repo](https://mvnrepository.com/artifact/com.github.spice-h2020/json2rdf)
- [CORD-19 RDF Covid-on-the-web](https://github.com/Wimmics/CovidOnTheWeb)
- [Dublin Core](https://en.wikipedia.org/wiki/Dublin_Core)
- [DBLP](https://dblp.org/)

Tasks to do:
- Search for RDF and CSV datasets on COVID and Healthcare
- Datahubs: [zenodo](https://zenodo.org/) and [datahub](https://datahub.io/)
- Update mappings for current COVID and Healthcare resources (i.e. COVID and COVID-Symptoms)
- Learn different dbpedia types (i.e. dbo, dbp, dbr, dbo, dbt, dbc)

July 7th 2021 meeting
Tasks to do:
- TARQL mapping from CSV to RDF
- Existing mappings updates (e.g. pendamicDeaths to pandemicDeaths)
- Questions/Info relating to Heathcare/COVID (e.g which vaccines are administered in each country?)
- Search Wikipedia and DBpedia resources in the healthcare field; check mappings
- Build sparql query for searching healthcare info

## Potential Datasets:
- COVID cases and deaths worldwide: [Datahub Novel Coronavirus 2019 COVID-19](https://datahub.io/core/covid-19#data)
- Pharmaceutical Drug Spending: [Datahub Pharmaceutical Drug Spending](https://datahub.io/core/pharmaceutical-drug-spending#pandas)
- World Vaccination Progress: [Kaggle COVID-19 World Vaccination Progress](https://www.kaggle.com/gpreda/covid-world-vaccination-progress)
- World Vaccine Adverse Reactions: [Kaggle COVID-19 World Vaccine Adverse Reactions](https://www.kaggle.com/ayushggarg/covid19-vaccine-adverse-reactions)
- Diabetes: [Datahub Diabetes](https://datahub.io/machine-learning/diabetes#r)
- Covid-19 Vaccine by Country: [Kaggle Latest Worldwide Covid19 Vaccine Data](https://www.kaggle.com/anandhuh/latest-worldwide-vaccine-data)
- Vaccine Preventable by Disease name: [Kaggle Vaccine Preventable Diseases](https://www.kaggle.com/rishidamarla/vaccine-preventable-diseases)
- [Kaggle World Vaccination Progress](https://www.kaggle.com/kingabzpro/world-vaccine-progress)
- [Kaggle World Health Statistics 2020](https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete)
- [COVID Mapping](https://coronavirus.jhu.edu/map.html)
- [COVID Worldometer](https://www.worldometers.info/coronavirus/)
- [COVID 19 dataset by date](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset?select=covid_19_data.csv)
- [DBpedia Live](https://www.dbpedia.org/resources/live/)
