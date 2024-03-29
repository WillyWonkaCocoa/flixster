# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

Time spent: 6 hours spent for this part

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="https://imgur.com/7L683kW.gif"/> 


GIF created with [LiceCap](http://www.cockos.com/licecap/).

### Notes
Connecting the segue to MovieDetailsVC in CollectionView was especially challenging. It took me about 30 minutes of searching on the web to find the solution.

---

## Flixster Part 1

Time spent: 9 hours spent in total

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device (iPhone 6S)
- [x] User can view the rating for each movie.

### App Walkthough GIF

<img src="https://imgur.com/QIvEu52.gif"/>


GIF created with [LiceCap](http://www.cockos.com/licecap/).

### Notes
Challenges encountered while building the app.

I run into issues creating my own custom cell. My app would crash with a "Thread 1 SIGABRT" error after I added the image view, and the cellForRowAt function never gets called. 🙁 Timothy from Codepath helped me resolve the issue through a quick exchange on Slack. Thanks Timothy!

## License

    Copyright [2019] [William Gao]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
