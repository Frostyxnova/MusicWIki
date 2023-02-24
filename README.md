# MusicWiki

MusicWiki is an unofficial Last.fm app that displays information about different music genres, albums, artists, and tracks listed under the genre. It uses the Last.fm API to fetch data and display it on the app.
## Features

- Display a list of genres available
- Clicking on the genre takes the user to a page containing information about it
- Display top albums, top tracks, and top artists as different sections on the genre page
- Display the cover image (if available) or default image, title, and artist name under each album
- Display the cover image (if available) or default image and name under each artist
- Display the cover image (if available) or default image, title, and artist name under each track
- Clicking on the album displays the cover image, title, artist information, description, and genres
- Clicking on the artist displays the image, title, play count, followers, description, a - list of top tracks and top albums, and the genres
- Clicking on the album/artist genre displays the details about the genre
- The app UI is designed to be user-friendly and easy to use




##  Tech stack
```
- kotlin
- last.fm Api
- Retrofit library
- Recycler Views
- Fragments
```
# Decisions and Assumptions
The following decisions and assumptions were made during the development of the MusicWiki app:

- Data Source: The app uses the Last.fm API to retrieve artist, album, and song data. This API was chosen because it provides a vast music library, including detailed artist information, top tracks, and album details.
## Assumptions:

- The API provides all the required data for the app
- The API response will always be in the expected format
- The user has an active internet connection to access the Last.fm API
# Decisions and Assumptions
The following decisions and assumptions were made during the development of the MusicWiki app:

- Data Source: The app uses the Last.fm API to retrieve artist, album, and song data. This API was chosen because it provides a vast music library, including detailed artist information, top tracks, and album details.
## Assumptions:

- The API provides all the required data for the app
- The API response will always be in the expected format
- The user has an active internet connection to access the Last.fm API

###
# Screenshots

# Genre 

![App Screenshot](https://res.cloudinary.com/dzu4lwzdc/image/upload/v1677243076/m2_ow0l3t.jpg)

#
# Genre detail

![App Screenshot](https://res.cloudinary.com/dzu4lwzdc/image/upload/v1677243076/m3_htj7di.jpg)


#
# Artist

![App Screenshot](https://res.cloudinary.com/dzu4lwzdc/image/upload/v1677243062/mu4_nany02.jpg)

#
# Album

![App Screenshot](https://res.cloudinary.com/dzu4lwzdc/image/upload/v1677243061/m4_k5zasi.jpg)

