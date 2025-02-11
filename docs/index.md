---
title:  Index
date: 2018-03-24 22:49:00
description: Our Geo-tutorial at The International Conference of Information Systems for Crisis Response and Management (ISCRAM) 2018 at Rochester Institute of Technology (RIT), Rochester, NY.
---

# Location Extraction and Georeferencing in Social Media: Challenges, Techniques, and Applications

Ability to extract or estimate location in social media content, and perform location-centric analyses offer unique and wide-ranging applications. Examples include disaster management, demographic and socio-cultural studies, and spatiotemporal tracking. For instance, location information is critical to reach and rescue disaster-stricken people and dispatch humanitarian assistance. Consequently, there is a pressing need for better understanding of how people express location information explicitly and implicitly on social media, and in general, develop efficient techniques for geospatial computing that spans all information channels. Additionally, location information enables a variety of individual-level and community-level analyses.

Location extraction and georeferencing methods leverage the user-generated content (textual as well as multimedia data, e.g., images, videos), and users’ connectivity (social network analysis). The applications of these methods range from detecting communities and localizing individual texts or detecting users’ physical locations. However, due to the challenges posed by social media data some techniques did not work reliably on its informal and ill-formed texts or scaled poorly.

In this tutorial, we present the general problem of georeferencing and location extraction, summarizes the state-of-the-art research, discusses challenges, and provides an overview of our recent research accomplishments in the context of disaster management. Furthermore, we provide a hands-on session to get the audience engaged in the process of location retrieval and extraction from social media.

---

# TUTORIAL TOPICS

* Geo-context and Geosemantics:
  * Geospatial Semantics, Technologies, and Data Interoperability.
* Location Inference and Geocoding:
  * Top Down Approaches:
    * Employing knowledge-bases  (e.g., knowledge graphs, ontologies, gazetteers)
  * Bottom-up Approaches:
    * Natural Language Processing (NLP) and Statistical Models  (e.g., language modeling)
    * Deep/Machine Learning technologies  (e.g., LSTMs and CRF for sequence labeling)
  * Social Network Analysis
    * Community detection and graph analysis
* Applications:
  * Disaster-specific applicatons (e.g., Storm surge modeling, traffic-related modeling, rapid disaster response, disaster recovery, emergency management, crisis visualization)
  * Socio-cultural and demographic studies (e.g., post-disaster depression studies)
  * Location-aware services (e.g. recommender systems, opinion analysis)
* Hands-on Session:
  * During this session, we will demonstrate to the audience how machine learning can be used to extract location information and show illustrative examples highlighting the challenges and faults of some of the location extraction systems.

---

# TUTORIAL SCHEDULE

<table>
<col width="40">
<col width="260">
  <thead>
    <tr>
      <th>Time</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">9:00am - 10:00am</td>
      <td>Motivate the location inference problem and introduce the concepts behind geospatial context and location-based techniques and applications.</td>
    </tr>
    <tr>
      <td align="center">10:00am - 10:30am</td>
      <td>Break</td>
    </tr>
    <tr>
      <td align="center">10:30am - 12:00pm</td>
      <td>More detailed technical and state-of-the-art technology for georeferencing and geocoding from social media texts and networks. We will discuss specific applications and future directions in the field.</td>
    </tr>
    <tr>
      <td align="center">12:00pm - 1:00pm</td>
      <td>Lunch</td>
    </tr>
    <tr>
      <td align="center">1:00pm - 2:30pm</td>
      <td>Continuing the last session topics</td>
    </tr>
    <tr>
      <td align="center">2:30pm - 3:00pm</td>
      <td>Break</td>
    </tr>
    <tr>
      <td align="center">3:00pm - 4:00pm</td>
      <td>Hands-on Session</td>
    </tr>
  </tbody>
</table>

---

# Geotutorial Resources

## Slides

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT38WjLamxvnlBwuOc8IArh1b7yu4iR15rWtjro9Z8NYFgH4Rmyyf4h-AmZT52S7iDxn6w9wQfr7yw3/embed?start=false&loop=false&delayms=3000" frameborder="0" width="80%" height="535px" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## Codes

* [<img src="https://raw.githubusercontent.com/halolimat/LNEx/master/LNEx_logo.png" style="width:80px;">](https://github.com/halolimat/LNEx){:target="_blank"}

* Jupyter Notebook 1: Geotutorial_Location_Extraction_Supervised_Models_(Notebook-1).ipynb

* Jupyter Notebook 2: Illustrative_Examples_Comparing_Tools(Notebook-2).ipynb

## Data

* [<img src="https://wwwdb.inf.tu-dresden.de/opendatasurvey/img/opendata1.png" style="width:180px;">](https://drive.google.com/drive/u/1/folders/1g_We4a17x3OkcE8CTSF8_MtvPouZ6CMz){:target="_blank"}


---

# TUTORIAL PRESENTERS AND COLLABORATORS

## Hussein S. Al-Olimat
* hussein@knoesis.org
* Kno.e.sis, Wright State University
* Hussein is a graduate researcher at Kno.e.sis-Ohio Center of Excellence in Knowledge-enabled Computing. His research spans the areas of Natural Language Processing, Information and Knowledge Retrieval and Extraction, Machine Learning, and Social Media Analysis. He is the lead researcher (at kno.e.sis) on the NSF-funded project “Social and Physical Sensing Enabled Decision Support for Disaster Management and Response” (HazardSEES) in collaboration with Ohio State University. His Location Extraction tool (LNEx) is now being integrated with the DEEP platform, a joint initiative by seven key humanitarian organizations: UNOCHA, UNHCR, OHCHR, IDMC, JIPS, ACAPS and IFRC.

## Amir Hossein Yazdavar
* amir@knoesis.org
* Kno.e.sis, Wright State University
* Amir is a researcher at Kno.e.sis Center Wright State University.  He is broadly interested in applying machine learning (incl. deep learning) and semantic web (incl. creation and use of knowledge graphs for social media analytics). He has a particular interest in studying people’s behavior, psychological status, social connectivity, and community demographics in social media.

* Related projects:

    * Modeling Social Behavior Depression
    * Twitris 3.0 – Sentiment Analysis for Analyzing Presidential Election
    * Gender-Based Violence in 140 Characters or Fewer: A BigData Case Study of Twitter.
    * Recent publication focusing on studying geographical analysis of large-scale user-generated content on social media:
    * On the Challenges of Sentiment Analysis for Dynamic Events
    * Semi-Supervised Approach to Monitoring Clinical Depressive Symptoms in Social Media

## Krishnaprasad Thirunarayan
* tkprasad@knoesis.org
* Kno.e.sis, Wright State University
* Prof. Thirunarayan has  offered several  tutorials on “Trust Networks” and “Semantics-empowered Big Data Processing”, and has many publications that span the areas to be covered in this tutorial including “Understanding City Traffic Dynamics Utilizing Sensor and Textual Observations”, and “Extracting city traffic events from social streams”. He is also a collaborator on several NSF and NIH funded projects covering social data analytics and applications spanning crisis management to health informatics.

## Amit Sheth
* amit@knoesis.org
* Kno.e.sis, Wright State University
* Prof. Sheth has offered 30+ usually well-attended tutorials at some of the top conferences (e.g., WWW, VLDB, SIGMOD, ICDE, ICWSM). His tutorial with his former PhD student at ICWSM 2013 on a topic relevant to ISCRAM “Crisis Mapping, Citizen Sensing and Social Media Analytics for Response Coordination” has over 52,000 views. He has led or is leading several significant NSF and NIH funded projects of relevance to this topic area (involving social media and/or crisis management/coordination: eg., “Social Media Enhanced Organizational Sensemaking in Emergency Response,” and “Hazards SEES: Social and Physical Sensing Enabled Decision Support for Disaster Management and Response,” with well over 50 publications). Technology from these projects have been used for coordination during real crisis (e.g., 2014 Kashmir Floods, 2014 Uttarakhand Floods) that have received major international media coverage, for comprehensive simulation for first responders in Dayton area, and for commercialization leading to Cognovi Labs started with the technology licensed from the university research he led.  Some of his 55 keynotes covered topics relevant to this tutorial. He is one of the top authors in Computer Science, WWW and Semantic Web.
