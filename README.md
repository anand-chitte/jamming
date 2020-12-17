# Jamming

Jamming is a useless React app for creating new playlists with Spotify.

## Codecademy

Built for the final project of the [Codecademy - Web Development Path](https://www.codecademy.com/profiles/anand-chitte/certificates/5b32457b646caa5007c30975).

## Features

* Spotify Login — the first time a user searches for a song, album, or artist, Spotify will ask them to log in or set up a new account.
* Search by Song, Album, or Artist — a user can type the name of a song, artist, or album into the search bar and click the SEARCH button.
* Populate Results List — Jammming displays the list of returned tracks from the user’s query.
* Add Song to a Custom Playlist — users can add a track to their playlist by selecting a + sign on the right side of the track’s display container.
* Remove Song from Custom Playlist — users can remove a track from their playlist by selecting a - sign on the right side of the track’s display container.
* Change Playlist Title — users can change the title of their custom playlist.
* Save Playlist to Account — users can save their custom playlist by clicking a button called SAVE TO SPOTIFY.

## Known issues

* Doesn't work with [Privacy Badger](https://www.eff.org/privacybadger) enabled 🦡😢

## Potential improvements

* ~~Pressing enter triggers a search~~
* Include preview samples for each track
* Only display songs not currently present in the playlist in the search results
* Add a loading screen while playlist is saving
* Update the access token logic to expire at exactly the right time
* ~~After user redirect on login, restoring the search term from before the redirect~~
* Ensure playlist information doesn’t get cleared if a user has to refresh their access token

## Codecademy Instructions

### Intro

> In this project, you will build a React web application called Jammming. You will use your knowledge of React components, state, and requests with the Spotify API to build a website that allows users to search the Spotify library, create a custom playlist, then save it to their Spotify account.

### Resources

> Because we want you to focus on building the React infrastructure, we have provided links to the HTML/CSS and visual assets below. Notice, we did not break the HTML and CSS into their components. To complete the project you will need to split the HTML/CSS into their components.

* [index.html](https://s3.amazonaws.com/codecademy-content/programs/react/jammming/static-html-css/indexHtml.txt) — all of the HTML for a static version of the website.
* [style.css](https://s3.amazonaws.com/codecademy-content/programs/react/jammming/static-html-css/indexCss.txt) — all of the CSS for a static version of the website.
* [image assets](https://s3.amazonaws.com/codecademy-content/programs/react/jammming/image_assets.zip) — all of the image assets used in the website.
