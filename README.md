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

![][up-coming]

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

__The Celebrity Page - Celebrity Card - Default Storybook.__
![][CelebrityPage-celebrityCard-default]


__The Celebrity Page - Celebrity Card - Exception Storybook.__
![][CelebrityPage-celebrityCard-default-exception]


__The Celebrity Detail Page - Celebrity Detail Storybook.__
![][CelebrityDetailPage-celebrityDetails]


__The Celebrity Detail Page - Celebrity List Storybook.__
![][CelebrityDetailPage-celebrityList]


__The Celebrity Detail Page - Celebrity Header Storybook.__
![][CelebrityDetailPage-celebrityDetailsHeader]


__The Movie Details Page - Similar Movies Button Storybook.__
![][movie-detail-similar-button]


### Server State Caching.

+ [Watch Demo Video: Server State Caching:](https://youtu.be/M7ARV0u_f_k).


+ [discover] - List of movies from the Discovery endpoint.
+ [movie,[id,:id]] - All properties for a particular movie.
+ etc

## Authentication.

[Briefly explain the method used for supporting authentication and include any relevant screenshots (e.g. Dev tools Network tab for session keys). State which parts of the app's functionality require authentication, e.g. the Favourites feature.]

## Algorithm (if relevant).

[State the purpose of the algorithm you chose to implement and explain, in general, the computation model used.]

## Additional Information.

[Highlight any other aspects of your app's design or implementation that is non-standard and worthy of mention.]

[up-coming]:   ./images/up-coming.png
[now-playing]: ./images/now-playing.png
[top-rated]:   ./images/top-rated.png
[celebrities]:   ./images/celebrities.png
[celebrity-details]:   ./images/celebrity-details.png
[show-similar-button]:   ./images/show-similar-button.png
[list-of-similar-movies]:   ./images/list-of-similar-movies.png
[full-detail-of-similar-movies]:   ./images/full-detail-of-similar-movies.png



[CelebrityPage-celebrityCard-default]:             https://i.imgur.com/H2R9Pvv.png
[CelebrityPage-celebrityCard-default-exception]:   https://i.imgur.com/qeSPwDW.png
[CelebrityDetailPage-celebrityDetails]:            https://i.imgur.com/xCjCTRH.png
[CelebrityDetailPage-celebrityDetails]:            https://i.imgur.com/rb0Kz9i.png
[CelebrityDetailPage-celebrityDetailsHeader]:      https://i.imgur.com/RDVj1My.png
[movie-detail-similar-button]:                     https://i.imgur.com/N8uMeRt.png
