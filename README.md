# Finder

Finder is a web application which allows its users to search for food around their locations.

## Technologies To Be Used

- HTML5
- CSS3
- JavaScript
- React
- PostgreSQL
- Node.js
- Express.js
- jQuery
- Media Queries
- Bootstrap
- APIs

## Live Demo

Try the application live at [finder.com](https://finder.waynedaniels.net/)

## Features

-   User can log-in with user name
-   User can log-in as a guest
-   User can sign-up with a desired user name
-   User is greeted with a message containing their user name
-   User can view profile page to locate "search", "location", "logout" button
-   User can set a search location
-   User can search restaurants by keywords
-   User can view stack of cards containing the restaurants results
-   User can "like" or "dislike" the restaurant card to move to next card
-   User can "rewind" to move back to the previous card
-   User can view details of the restaurant on click
-   User can view "liked" restaurants
-   User can view "reviewed" restaurants
-   User can write review from the list of liked restaurants

## Preview

![](server/public/images/finder.gif)

#### Getting Started
1. Clone the repo
  ```shell
  git clone https://github.com/john-jaihyek-choi/finder.git
  ```
2. Change directory to cloned folder
  ```shell
  cd finder/
  ```
3. Install all dependencies with NPM
  ```shell
  npm install
  ```
4. Start PostgreSQL database server
  ```shell
  sudo service postgresql start
  ```
5. Create the database
  ```shell
  createdb finder
  ```
6. Import the schema and dummy data
  ```shell
  npm run db:import
  ```
7. Access the finder Postgresql database server using pgweb in your default web browser
  ```shell
  pgweb --db=finder
  ```
