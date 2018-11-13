# YelpMe

## Table of Contents
  * [Collaborators](#team-members)
  * [Introduction](#intro)
  * [Functionalities](#func)
  * [Project Demo](#proj-demo)
  * [Limitations](#lim)
  * [Future Prospects](#var)
  

## <a name ="team-members"></a> Collaborators
* [Pranav Bhasin]
* [Muskaan Goyal]

## <a name ="intro"></a> Introduction
In this project, we attempt to create an accurate visualization of restaurant ratings using the [Yelp academic dataset]. We implement this idea using a [Voronoi tessellation]-based visualization of restaurants in the city, clustering restaurants using [K-Means] algorithm on the basis of their proximity to other restaurants and using Linear Regression to predict a user's ratings, to display the nearest restaurants to locations on the basis of their preference to the user.

<p align = "center"><img src = "https://github.com/PranavBhasin001/YelpMe/blob/master/visualize/voronoi.png"></p>
<p align= "center"> Voronoi Diagram for Restaurants in Berkeley </p>

The visual above segments Berkeley into regions, where each region is shaded by a color from yellow to blue (i.e 5 to 1 stars), representing the predicted rating of the closest restaurant and forming a Voronoi tessellation in the process. 
Each dot represents a restaurant. The color of the dot is determined by the restaurant's location. 
For example, downtown restaurants are colored green. The user that generated this map has a strong preference for Southside restaurants, and so the southern regions are colored yellow.

## <a name ="func"></a> Functionalities

## <a name ="proj-demo"></a> Project Demo

## <a name ="lim"></a> Limitations
**1. Distance Calculations:**
  * Instead of using [Euclidean Distance], we could use [Hamming Distance], or [Manhattan Distance] to better simulate walking/driving distances in  cities.
  * Alternatively, we could use a modified form of Euclidean Distance to simulate the difference due to the curvature of the Earth.
  
**2. Limited Dataset**
  * The academic dataset is limited to 30 cities near Universities and we are currently only using data for the Berkeley. The Yelp API could be utilized to expand the scope of this project

## <a name ="var"></a> Future Prospects

[Voronoi tessellation]: https://en.wikipedia.org/wiki/Voronoi_diagram
[Euclidean Distance]: https://en.wikipedia.org/wiki/Voronoi_diagram
[Hamming Distance]: https://en.wikipedia.org/wiki/Voronoi_diagram
[Manhattan Distance]: https://en.wikipedia.org/wiki/Voronoi_diagram
[Pranav Bhasin]: https://github.com/PranavBhasin001
[Muskaan Goyal]: https://github.com/muskaangoyal
