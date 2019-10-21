## Hackathon: HackHarvard
### Location: Harvard University
### Date: October 2019
### Awards: 
Facebook Best Hack for Building Community or Connecting People, Hacker Spirit Award

#### Summary:

Project: [Act Now](https://devpost.com/software/act-now)

This hack won the Facebook building community award and the MLH Hacker Spirit Award. Our team of 4 built a Chrome extension with the goal of turning frustration when reading about the news to tangible actions one can take. The extension works by taking the user's current URL and scraping article contents, matching keywords with organizations and events stored in a backend database, and returning a popup to the user with a relevant organization to take action.

The devpost link above links the Bitbucket backend repo (branch: api\_debugging) and Github frontend repo. You can also see a demo video, detailed descriptions and official awards won. The chrome extension itself is pending approval on the Chrome web store.

Technical details:
* REST API to communicate between frontend and backend
* Frontend: ReactJS Chrome extension (built by Simon)
* Backend: Django App hosted on Heroku 
  * Python web scraper/parser with BeautifulSoup4 (built by me)
  * Python keyword extractor and matcher (built by Owen)
  * Django models (built by Noor)

![Group Picture!](https://github.com/SGinovker/HackathonProjects/blob/master/_img/group_photo.png)

![Demoing](https://github.com/SGinovker/HackathonProjects/blob/master/_img/demoing.png)
