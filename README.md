# dbpedia-GSoC2021
Google Summer of Code 2021 DBpedia Healthcare Platform project by Guang Zhang. Project link: [https://github.com/dbpedia/healthcare-platform](https://github.com/dbpedia/healthcare-platform)

## Proposal
[Proposal for Healthcare Platform](https://docs.google.com/document/d/1kGc_-2c9FV_pjw5Y0rD3VW8jecGz4Q5MlsqZKiIYpZ8/edit#)

## Goals
- Research COVID19 and healthcare datasets, and create mappings with sparql queries, then upload to DBpedia databus
- Contribute to the DBpedia mapping ontologies and healthcare field
- Deploy a (DBpedia interlinked) healthcare dataset on the DBpedia Databus
- Community Release Extension for COVID-19 HEALTHCARE

If times allow: 
- Create a Dashboard
- Healthcare QA using this dataset
- demo QA using SPARQL

## COVID Mapping for Data Sets
[COVID-Mapping](https://drive.google.com/file/d/148L6tIGYblEgEZtLZ-LThCvaYY_jla29/view?usp=sharing)

## Resources
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
- [DBpedia Web](https://www.dbpedia.org/)
- [Github Repo](https://github.com/dbpedia)
- [Get familiar with DBpedia Sparql databus](https://github.com/dbpedia/virtuoso-sparql-endpoint-quickstart)
- [GSoC 2020 Dashboard](https://github.com/dbpedia/gsoc-2020-dashboard)
- [CORD-19: The Covid-19 Open Research Dataset](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7251955/)
- [Analyse and compare recency/correctness of Wikidata to recency/correctness of Wikipedia/DBpedia](https://svn.aksw.org/papers/2020/qurator_gfs/public.pdf)
- [SPARQL wikidata](https://www.wikidata.org/wiki/Wikidata:SPARQL_tutorial)
- [SPARQL w3](https://www.w3.org/TR/sparql11-query/)

## Potential Healthcare Datasets:
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


## Meetings

June 15h 2021 Meeting.
Discussed sparql, rdf turtle tools, articles reading.
Tasks to do:
- Explore Tarql mapping tools
- Read articles about wikipedia, wikidata, CORD-19 dataset
- Get familiar with sparql query

June 23rd 2021 Meeting.
Discussed DBpedia ontology and json2rdf tools
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

July 7th 2021 Meeting.
Tasks to do:
- TARQL mapping from CSV to RDF
- Existing mappings updates (e.g. pendamicDeaths to pandemicDeaths)
- Questions/Info relating to Heathcare/COVID (e.g which vaccines are administered in each country?)
- Search Wikipedia and DBpedia resources in the healthcare field; check mappings
- Build sparql query for searching healthcare info

July 13th, July 16th 2021 Meetings.
Tasks to do:
- Describe statistics for the fields of the CSV files (e.g. Confirmed Cases and Deaths by Country, Vaccines and Total Vaccine Doses by Country)
- Check existing mapping in healthcare, COVID, and create new mappings if not existed or linked
- Continue mapping for the CSV files using Tarql

July 22nd 2021 Meetings.
Discussed Data set statistics, DBpedia mappings and ontology. 
Tasks to do:
- Create Mappings for the [Kaggle COVID-19 World Vaccination Progress](https://www.kaggle.com/gpreda/covid-world-vaccination-progress)
- Check existing mapping in healthcare, COVID, and create new mappings if not existed or linked
- Continue mapping for the CSV files using Tarql

July 26th 2021 Meeting.
Discussed Tarql Mapping, Databus upload.
Tasks to do:
- Convert Git repo on DBpedia (Heath platform) to Git LFS
- Learn lbzip2 compression
- Upload the compressed data set with Git LFS to the DBpedia repo
- Learn DBpedia databus
- Upload the World Vaccination Progress with Databus

August 2nd 2021 Meeting.
Set up ssh dbpedia server and SSH key together; set up webid for the Databus upload
Tasks to do:
- Try again for the DBpedia databus upload
- Prepare data sets for healthcare
- Try again maven databus

August 5th 2021 Meeting.
Discussed Tarql Mappings
Tasks to do:
- Use Kaggle API for downloading data sets
- Continue mapping

August 9th 2021 Meeting.
Discussed Kaggle API and DBpedia databus upload
Tasks to do:
- Shell scripting and web scrapping for checking kaggle versions
- Download data set only if newer version is available
- Fix Tarql Mapping
- Check again DBpedia web upload for databus

August 12th 2021 Meeting.
Discussed missing webid files and fixed the issue by taking backup copy; Discussed cronjob for auto-updating
Tasks to do:
- continue version checking for kaggle data sets
- re-organize data sets and databus-upload (e.g. raw for csv files only, namings of folders and data sets)
- check dbpedia mappings contributions

August 16th 2021 Meeting.
Discussed DBpedia databus progress; schedules and plans for GSoC2021 submission
Tasks to do:
- Tarql mapping for data sets
- Fix mapping issue
- Continue version checking for kaggle data sets

August 18th 2021 Meeting.
Discussed databus-upload folder structure, github repo, GSoC2021 submission
Tasks to do:
- Re-organize folder structure
- Download each data set again, only csv files, put them into 2021.08.18 folders
- Run tarql mappings for all again, and put them into folder "input"
- Rename them based on the example (_tag=default.csv.bz2)
- Enter empty pom.xml files and Description .md files
- Github repo re-organize

