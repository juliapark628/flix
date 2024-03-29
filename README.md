# Project 2 - Flix

Flix is a movies app using the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

Time spent: **17** hours spent in total

## User Stories

The following **required** functionality is complete:

- [x] User can view a list of movies currently playing in theaters from The Movie Database.
- [x] Poster images are loaded using the UIImageView category in the AFNetworking library.
- [x] User sees a loading state while waiting for the movies API.
- [x] User can pull to refresh the movie list.

The following **optional** features are implemented:

- [x] User sees an error message when there's a networking error.
- [x] Movies are displayed using a CollectionView instead of a TableView.
- [x] User can search for a movie.
- [ ] All images fade in as they are loading.
- [x] User can view the large movie poster by tapping on a cell (for both collection and table view)
- [ ] For the large poster, load the low resolution image first and then switch to the high resolution image when complete.
- [ ] Customize the selection effect of the cell.
- [ ] Customize the navigation bar.
- [ ] Customize the UI.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. There are some functionalities that we repeated (such as creating URLs, fetching movies, etc) that were simply copy-pasted between view controllers. Maybe we should create a separate class with those methods and import/extend these methods as necessary instead of manually copy pasting them. 
2. It would be cool to let the user favorite certain movies and then show all those movies in a different tab. How would we store the array of movie-objects and pass it between view controllers? 

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://g.recordit.co/ED6Pk4eiAg.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />
<img src='http://g.recordit.co/xt85RrEgSR.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Recordit](http://recordit.co).

## Notes

Describe any challenges encountered while building the app.

It was challenging but interesting to implement features that did not have video tutorials, like the activity indicator and the no-network alert, because it made me really think about what I was coding and how the entire program's flow was structured. 

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library
- flix-assets from CodePath
- [The Movie Database API](http://docs.themoviedb.apiary.io/#)

## License

    Copyright 2019 Julia Park

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
