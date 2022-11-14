# STRAPI Movie Database

## Developer: Eli Ewa

## Project Description

This is a movie database web app that I am building for myself to use personally and also add to my portfolio. As a big movie fan who is always wondering what to watch next and what is popular at the moment, I find an app like this one to be quite useful and a fun way to offer users a vast amount of information with very little complexity. My goal for this project is to implement a random movie generator which will take info about the users interests and generate a list of movies/tv shows from an API which most closely match their interests. In addition to this, the site will act as a simple database where users can browse endlessly through 100's of movies and tv shows and be directed to websites where they can purchase or stream them.

### Site Map link => https://www.figma.com/file/OnfcgjURFkKGfkXiAqGNnl/strapi-moviedb?node-id=0%3A1&t=gqo4u6CPBLP74Nia-1

## Extras

Components: I made a "description" component to group the common description elements together for movies and t.v shows.

Relation fields: I created two separate relation fields, one for "genre" and another for "reviews". I decided to make them "one to many" since one movie can have multiple genres and reviews. 