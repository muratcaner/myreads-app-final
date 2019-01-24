# MyReads Project

In this project, students are to write React code to make the project look like a local [GoodReads](https://www.goodreads.com/). CSS and HTML are provided. 

## How to Install

* Clone the project here:
  - https://github.com/Caysle/myreads-app-final.git

* install all project dependencies with `npm install`
* start the development server with `npm start`

## Important
The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend, so don't be surprised if your searches for Basket Weaving or Bubble Wrap don't come back with any results.

## Dependencies

* This project was made by using [Udacity's myReads starter code](https://github.com/facebookincubator/create-react-app). 
* [React Router](https://www.npmjs.com/package/react-router-dom) was installed to make the app work properly.
* To simplify students' development process, a backend server was provided for students to develop against. The provided file [`BooksAPI.js`](src/utils/BooksAPI.js) contains the methods students will need to perform necessary operations on the backend:

  - `getAll`
  - `update`
  - `search`

