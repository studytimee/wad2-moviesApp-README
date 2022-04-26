# Enterprise Web Dev - Assignment 1.

__Name:__ [your name]

### Overrview.

+ Add Card to WatchList 
+ Remove Card from watchList
+ When the watch list is selected, the avatar of the watch list appears on the card.
+ Support Storybook for each component.
+ Upcoming, Top-rated, similar movies, Celebrity, Celebrity Details.
+ Similar Movies Button in the movies detail page. Click and view full details.
+ User Authentication (External Auth via Security Web Token)
+ Private Routes: 2 Private routing
+ Routes : 4 static routes and 3 parameterised routes
+ Web Form (SignUp)
+ Server State Cache (useQuery)
+ Dynamic and interactive UI, Material UI, Styled 3rd Party components.
+ Celebrity search by name
+ Sorting popular celebrity


## Feature Design.

__The Upcoming Movies feature.__
![][upcoming]
> Lists movies from the Upcoming movies endpoint of TMDB
__URL:__ /movies/upcoming


__The Now Playing Movies feature.__
![][now-playing]
> Lists movies from the Now-playing movies endpoint of TMDB
__URL:__ /movies/now-playing


__The Top-rated Movies feature.__
![][top-rated]
> Lists movies from the Top-rated movies endpoint of TMDB
__URL:__ /movies/top-rated


__The Celebrities feature.__
![][celebrities]
> Lists of Celebrities endpoint of TMDB
__URL:__ /movies/actors/home


__The Celebrity Detail feature.__
![][celebrity-details]
> Show the detail of selected celebrity endpoint of TMDB
__URL:__ /movies/actors/{actor-id}


__Showing the similar button feature.__
![][show-similar-button]
> Similar button shows in the movies details page


__Show the list of similar movies feature.__
![][list-of-similar-movies]
> List of similar movies match with the selected movie_id
__URL:__ /movies/{selected-movie_id}


__Show the full detail of similar movies feature.__
![][full-detail-of-similar-movies]
> Show the full details of movie id form the matched list.
__URL:__ /movies/{new-matched-movie_id}



## Storybook.

[Include a screenshot(s) from the Storybook UI and highlight the stories for new components developed.]

e.g.

![][image5]


### Server state caching.

[Show a screenshot(s) from the react-query Dev tools that illustrate all the entity types cached by your app (Use appropriate magnification for accessibility). State the type of data relating to each cache entry.]

+ [Demo Video](https://youtu.be/M7ARV0u_f_k).




![][image4]

+ [discover] - List of movies from the Discovery endpoint.
+ [movie,[id,:id]] - All properties for a particular movie.
+ etc

## Authentication.

[Briefly explain the method used for supporting authentication and include any relevant screenshots (e.g. Dev tools Network tab for session keys). State which parts of the app's functionality require authentication, e.g. the Favourites feature.]

## Algorithm (if relevant).

[State the purpose of the algorithm you chose to implement and explain, in general, the computation model used.]

## Additional Information.

[Highlight any other aspects of your app's design or implementation that is non-standard and worthy of mention.]

[upcoming]:   https://i.imgur.com/wdrCaBM.png
[now-playing]: https://i.imgur.com/BPVrKpK.png
[top-rated]:   https://i.imgur.com/HBXIaKP.png
[celebrities]:   https://i.imgur.com/G9sYjxh.png
[celebrity-details]:   https://i.imgur.com/rDdEJyH.png
[show-similar-button]:   https://i.imgur.com/dH6QVU6.png
[list-of-similar-movies]:   https://i.imgur.com/hHOjnFw.png
[full-detail-of-similar-movies]:   https://i.imgur.com/V3DegSO.png


  
