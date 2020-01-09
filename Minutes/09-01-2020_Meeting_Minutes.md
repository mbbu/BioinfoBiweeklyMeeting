# Minutes for the first MBBU meeting of the year 2020

## Date: Thursday 9, January 2020
 
## Time scheduled for meeting:  1000hrs-1200hrs

## Agenda Items

1. Introductions and welcome 
2. Presentation and Demo on Data Management Platform 
3. Update on the status of the HPC, ReDCap migration to the cloud and the plan going forward 
4. Year-long Bioinformatics training activities update from Ouso 
5. Update and Calendar on Open Science activities and seminars by Caleb 
6. AOB 


## Present

1. Dr.Caleb Kibet
2. Careen Naitore
3. Geoffrey Kimani
4. Cynthia Kamau
5. Festus Nyasimi
6. Pauline Karega
7. Dr.Jandouwe Villinger
8. Glen Sequeira 
9. Dr.Henri Tonnang
10.Gilbert Kibet
11.Kennedy Mwangi
12.Karen Wambui
13.Daniel Ouso
14.Bwanya Brian
15.Eric Kariuki

## Absent
1. Andrew Espira
2. Dr. Daniel Masiga
3. Christian Mumo

## Agenda 1: Introductions and Welcome.

Dr. Caleb Kibet started the meeting at 1005hrs with a welcome message and introductions from everyone present
He talked about full implementation of the MBBU strategy by end of the year 2020
Everyone present introduced themselves, talked about what they are currently working on and their expectations for the year 2020


## Agenda 2: Presentation and Demo on Data Management Platform (Geoffrey and Cynthia)

## System architeture (Geoffrey)

Introduction to RedCap
Storage of data in icipe repository
Working API
Data importation from REDCAP

## Design Principles
 
SOLID PRINCIPLES such as Modularity of system, singleness of responsibility, opennes and closedness of the system
Security of data stored on the system with regards to data encryption
Hosting of data to a cloud service MS Azure


## DEMO OF THE PROTOTYPE (Cynthia)

Demonstration on:
i. how to fill in the REDCAP form for sample request
ii.The Sample management dashboard with various tabs 
iii.Managing different data such as genomic data, GEIS data
iv. Approval of sample requests by System admin

## Suggestions from Dr. Villinger - Instead of the Dashboard having specific studies, it should be grouped in terms of project in which samples were collected
## Suggestion from Festus - Metadata should indicate samples remaining after use 
## Follow-up from Ouso & Villinger - Amount of sample remaing should also include the date e.g.  available sample amount as of 9/1/2020 is 10ml
## System users should be able to know if requested sample is available or not and the next steps

## Suggestions from Dr. Henri Tonnang

## Rethinking of the whole system concept all the way from a data warehouse
## A nested loop for the sample management dashboard - a hierarchical approach
## Dynamism in the system. He talked about reconfiguration of the whole system to include icipe research activities
## He also suggested a technical meeting to discuss redesign of the Data management system
## Consolidation of the data management into a centralized database
## How icipe project collaborators and partners will access the system
## Finding publicly available data from a search engine such as google 
## He recommended the Geonode repository   

## Suggestion from Glen: The API should allow querying of the system and access on the centrewide icipe  website

## Comments from Dr. Caleb Kibet
# Sample management system is a module of the data warehouse
# Data warehouse will host other information such as genomics data, scripts and pipelines

 

## Agenda 3:  Update on the status of the HPC, and the plan going forward

# He talked about upgrading of the server to ubuntu
# Migration of RedCap to the cloud is pending

# Comment from Glen: Migration to cloud requires license approval


## Agenda 4: Year-long Bioinformatics training activities update from Ouso 

# Ouso started with a recap of training activities in the year 2019

# 4 trainings were conducted at icipe as follows:

i. July - Introduction to Data Management
ii. July - EANBiT Residential training
iii. August - H3ABionet 16SrRNA Intermediate Bioinfromatics Training
iv. December - Data Carpentries Workshop

# He then talked about the trainings scheduled for 2020 as follows:

## 1. MARCH - Data Management for Open and Reproducible Genomics Research Workshop (2 days)
# The targetted audience will be life science researchers interested in genomics research and involved with genomic data management

## Modules to be covered:
• Introduction to bioinformatics
• Organizing a genomic project workspace (Data Management Plan)
• Open and reproducible Bioinformatics research (Data tidiness, Frictionless Data tools)
• Introduction to data backup and version control (Git and GitHub, Pipeline tools)

## 2. JULY - AUGUST EANBiT Residential Training Course (6 weeks)

# Targetted audience: Graduate students with familiarity to computing/programming.

# Modules to be covered 

• Version control and collaborative development (Git & Github)
• Advanced Scripting
• Biological databases and API
• Gene models and annotation
• Reproducibility and package management: workflow languages (CWL &  Snakemake)
• Phylogenomics (Visualization and Annotation)
• Metagenomics (16S and Whole genome shotgun sequencing) 
• Machine Learning and modeling for big data (HMM)

## 3. AUGUST - OCTOBER: H3ABioNet: Intermediate 16S rRNA Microbiome Training Course

# Targetted audience: Life science researchers involved in genomics data analysis

# Modules to be covered 

Introduction to the Linux command line / intro to R
• Introduction to the microbiome and study design – why 16S?
• Sample collection, extraction and library prep for 16S NGS analyses
• 16S rRNA gene amplicon sequencing bioinformatics pipeline: the theory
• 16S analysis pipeline - QC, ASV picking, taxonomic classification and alignment metagenomeSeq (among others)
• Downstream analysis in R - using the packages phyloseq, NMF, vegan

## 4. DECEMBER Data Carpentry Genomics Workshop (4 days)

# Targetted audience: Life science researchers

# Modules to be covered

• Project organisation and management
• Introduction to command line interface
• Data wrangling and processing
• Introduction to cloud computing
• Introduction to R and RStudio for genomics

## Comments from Dr. Caleb 

# He talked about the upcoming launch of the Bioinformatics hub of Kenya
# Incorporation of the Carpentries training within the Bioinformatics Hub activities
# Capacity Builiding within the Bioinformatics Hub of Kenya

## Additional comments from Festus on the Bioinformatics Hub of Kenya

# Scheduled Launch of the Hub (January or February 2020)
# Peer learning within the hub
# Workshops and trainings within the hub's year long activities
# Mentorship and outreach

## Suggestions fro Dr. Henri Tonnang

# Reactualization of training modules and integrating them all under Data Science seconded by Dr. Caleb

## Update from Karen Wambui on Financing of Training activities

# EANBiT Residential training fully financed by the EANBiT Project
# Other training courses are financed by both H3ABionet and EANBiT
# She also stated that this Year's EANBiT Residential training targets only EANBiT Fellows as opposed to the previous year which had reseachers & students from other institutions
# Trainers and mentors of the Training activities provided for with accomodation and travel costs

## Suggestions from Dr. Henri Tonnang

# Timetable for the training activites
# Developing of proposals centred around the training to allow for grant applications
# Exploring income generating options such as application fees for training
# Having an exit strategy after trainings are completed

## Suggestions from Dr. Villinger seconded by Dr. Henri Tonnang

# Recording of videos of on-going training sessions and uploading them to the website for public availability

## Comment fro Dr. Caleb: Github repo already exists with previous training material 

## Agenda 5 : Update and Calendar on Open Science activities and seminars by Caleb

# Dr. Caleb informed students present that the next meeting will target improving their presentation skills
# He also talked about his Mozilla Fellowship commitment
# Accreditation of Pending activities


## Suggestions from Dr. Henri Tonnang

# He talked about formation of a Data Modelling and Geioinformation unit as an umbrella unit for all the data related courses and activities within icipe
# Having a generic concept that deals with data by end of the year  


## AOB

# Securing of facilities currently used by the Bioinformatics group
# Permanent setup of the Bioinformatics lab

## Suggestion from Dr. Henri Tonnang

# Having one wing of R&D for Data Modelling and Geoinformation unit


## Next meeting scheduled for 23 January 2020
