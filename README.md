# MoreAIRAsthmaKGxE


## About The Project 

AsthmaKGxE is carried out within the MoreAir project, which is funded by the Belgium Ministry of cooperation through the VLIR UOS program under grant MA2017TEA446A101. The MoreAIR project studies urban pollution and its impact on infant respiratory health. 

AsthmaKGxE is a biomedical AI-powered Asthma-centric Knowledge aiming to be a centralized hub for Asthma by extracting all relevant information from both genomic databases and the scientific literature, modeling and presenting it in a concise and queryable manner. AsthmaKGxE was built using Natural Language Processing and Data Mining techniques and was deployed using Big Data infrastructure. In this Asthma-centric Knowledge Graph, we include Genetic, Environmental, Psychological, Nutritional and socio-economic factors interacting and surrounding this chronic respiratory disease. We highlight these interactions in our GxE Catalog and present a searchable platform to browse the various relations linking Asthma, its genes, its comorbidities with many factors such as pollution, diet and anxiety. To complete AsthmaKGxE, we are currently developing Machine Learning and Deep Learning models to predict the most likely candidate relations such as candidate genes and potential environmental factors and interactions.

The online platform is available on : http://asthmakgxe.moreair.info/

## Built With 

- SciSpacy 
- Spacy
- Neo4j
- Cypher
- py2neo
- MongoDB
- Streamlit

## Getting Started :

### Data

| MongoDB | asthma papers |
| ----------- | ----------- |
| MongoDB | sentences |
| MongoDB | triplets | 
| Neo4j | Asthma KG |

### Data Collection 

| Web scraping | PMC |
| ----------- | ----------- |
| PMC | GxE/PMC-scraping |
| PMed | GxE/PMC-scraping | 

### Data Processing 

| Sentences | Spacy | GxE/get_sents | 
| ----------- | ----------- | ----------- |
| Entities | sci spacy models | NLP/get_entities_spacy |
| Entities | Bern | NLP/get_entities_bern_async |
| Entities | Bern | NLP/get_entities_bern_async |
| Entities | Custom Tags | NLP/get_entities_custom |
| Triplets | AllenNLP | NLP/relation_extraction |
| Triplets | CoreNLP | NLP/relation_extraction |
| Lemmatization of verbs | Spacy | NLP/proc_verbs |

### Graph Pred


| Link Prediction | Link prediction models test | LP/ | 
| ----------- | ----------- | ----------- |
| Graph Completion | completion | KG/completion |
| Graph Completion | merge | KG/merge |
| Graph Completion | early RF model | KG/RF-LP |



