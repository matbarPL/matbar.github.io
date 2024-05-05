+++
date = "2019-02-06"
title = "Recommender System for YELP users"
tags = ['recommender-systems', 'neural-networks', 'python']
+++

Recommender systems play an important role in many web services. Thanks to them Internet platforms can generate maximum profit and their clients be as satisfied as possible. In my thesis I focused on comparison of algorithms and then I implemented the best one in form of a web application. Neural networks are used as well due to their increasing popularity in recommendation tasks.

On index page app user has 4 main choices of recommendations:
- collaborative filtering where was used baseline model
- neural networks model with one hidden layer
- knn based algorithm
- content based algorithm

![index](/img/blog/recommender-system-for-yelp-users/index.png)

When user sends request to a server by filling a form he or she is redirected to the new page with the best recommendations.

![all](/img/blog/recommender-system-for-yelp-users/all.png)

Best tab shows level of similarity between a user and an item.

![best_one](/img/blog/recommender-system-for-yelp-users/best_one.png)

All recomendations are shown to a user based on his or her location (if the user hasn't changed the original one).

![on_map](/img/blog/recommender-system-for-yelp-users/on_map.png)

App was designed in a web app architecture where all the data is stored on a server.

![app_architecture](/img/blog/recommender-system-for-yelp-users/app_architecture.png)
*source: https://www.scnsoft.com/blog/web-application-architecture* 

Below you can find a video of the application.

{{< youtube tKwbLZ40nag >}}

