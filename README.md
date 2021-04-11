# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF
<img src="http://g.recordit.co/Sf06VR2MNd.gif"><br>
<img src="http://g.recordit.co/7x9lEQyQjn.gif"><br>

### Notes
One of the challenges I faced was understanding the concept of how data is passed from one view controller to another, since I was used to web development in which each page often used different API calls to view particular details of the Movie object. In this case, the information of the Movie object in the detail view is passed in from the main view controller.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF
<img src="http://g.recordit.co/2y4ePuKyj1.gif">
<img src="http://g.recordit.co/OwQL47urqP.gif"><br>
<img src="http://g.recordit.co/GH8NNFQ710.gif"><br>

### Notes
One of the main challenges was understanding the concept of using CocoaPods to allow for using open source libraries that aid the development process. I was able to fully understand when the reading pointed out its similarity to NPM for JavaScript, which reminded me that package managers are helpful to keep track of the libraries that your app is using and also easily use "modules" created by other developers.
