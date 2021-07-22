# Tourism Recommendation and Pathfinding System (A course work)
## Background
This project develops a website that recommends New Zealand attractions to the user based on their interests and help them plan the shortest path that passes all places they want to travel through. 

The recommender system is based on Collaborative Filtering (CF), which gives each attractions a score based on the user's preferences such as their mark of other attractions or their actions towards different attractions. In this project, the top 10 scored attractions are displayed as a recommendation list.

The path finding system uses Ant Conloy Optimism (ACO) to find the shortest path of attractions chosen by the user. It mocks the pattern of ants carrying foods back to their nest and generates more than 200 artificial ants on the map of attractions to inspect the shortest path of these spots.

![image](https://user-images.githubusercontent.com/18132007/126140355-2929ae38-b4c7-403f-babf-8d8a1af13a72.png)

## Implementation

### The recommendation system
1. On the homepage, users will see a recommendation list, which is a recommendation prediction based on the recommender system’s ratings of all users and the preferences of current users!

![homepage](https://github.com/Eric0625/TourismRecommendation/blob/main/pictures/Home.png "The home page")
***
2. The user browses the destinations through the Explore page, they can select a favourite travel destination and click on the picture or text to enter the detail page.
![AttractionList](https://github.com/Eric0625/TourismRecommendation/blob/main/pictures/AttractionList.png "AttractionList page")
***
3. The first half part of the detail page is the attraction's information and the rest on the page is a recommend list based on the user's attributes.  Users can perform two operations on this page, which are rating a tourist attraction, and adding it to Path Finder. After the user performs the rating, the recommender system will start to recalcualte the recommend list, and the detail page and homepage will be updated accordingly.

![AttractionList](https://github.com/Eric0625/TourismRecommendation/blob/main/pictures/Recommendations.png "Details and recommendations page")

### The Pathfinding System
1. A location is put in the PathFinder after the user add it on it's detail page. The PathFinder allows a maximum of 5 locations for maintaining calculation effciency.

![AttractionList](https://github.com/Eric0625/TourismRecommendation/blob/main/pictures/PathFinder.png "PathFinder page")
***
2. When the user clicks the Arrange The Path button, the system will plan the travel route for all destinations and display it on the map. In addition, the total distance of the travel itinerary is also displayed at the top of the page.

![AttractionList](https://github.com/Eric0625/TourismRecommendation/blob/main/pictures/PathofResult.png "PathFinding result page")

***
Credits:

Engine design: Qing Yuan

Web UI: Jay Liu
