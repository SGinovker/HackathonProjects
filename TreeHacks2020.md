## Hackathon: TreeHacks
### Location: Stanford University
### Date: February 2020

#### Summary:

Project: [RouteSafe](https://devpost.com/software/routesafe-uwqt4e)

The goal of this project was to make a navigation app for new drivers. The route calculation takes into account the 3 fastest routes to the destination (given using the MapQuest API AlternativeRoutes) combined with severity scores of accidents along each route. These are calculated based on historical accident data (MapQuest Traffic API) as well as live data, where accidents are ranked on a numerical scale based on severity. Each route is split into segments, where each segment has a linkID MapQuest uses to identify the road. Accidents are then looked up and summed for each linkID. The route with the lowest accident score of the 3 fastest routes is then returned. 

The devpost link above links the Github repos (contains both backend and frontend). 

Technical details:
* Backend: JavaScript functions hosted by Firebase on Google cloud (built by me + Brian)
  * MapQuest APIs are used for traffic data and to get alternative routes
* Frontend: iOS app in Swift (built by Josh)
* Data visualization: Map of traffic accidents, ranked by severity. Visualized using the Corta API (Krishna)

![Picture](https://github.com/SGinovker/HackathonProjects/blob/master/_img/treehacks.jpg)
