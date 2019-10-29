## Hackathon: YHack
### Location: Yale University
### Date: October 2019
### Awards:
EDR Best Graph Database Search and Compare

#### Summary:

Project: [Graph.srch](https://devpost.com/software/yhack-2019)

This project won the best graph database search and compare award from EDR. The goal of this project was to model the data given (csvs with address data over 3 years) in a graph database and perform different comparisons on it. Our web app implemented a matching algorithm to search our database using the user's specified criteria (ie state=MA) and also a comparison algorithm that returned differences between certain years. 

The devpost link above links the Github repo (contains both backend and frontend). 

Technical details:
* Backend: Python Flask web app (built by Dennis)
  * Neo4j database hosted on Google cloud (me)
  * Python data loader using Neo4j's Cypher query language (built by me)
* Frontend: ReactJS (built by Brandon)
  * UI concept designs (created by Kanupriya)

![Group Picture!](https://github.com/SGinovker/HackathonProjects/blob/master/_img/yhack19.png)
