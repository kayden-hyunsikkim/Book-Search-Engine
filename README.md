# Book Search Engine

## Table of Contents

- [Description](#description)
- [Technology](#Technology)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribution](#contribution)
- [Questions](#questions)

## Description:

This application allows users to search for new books from Google's Book API. Users can log in to save the book they would like to purchase, as well as to remove the books from their library.

## Technology:

Project is created with:

- MongoDB
- Express.js
- React.js
- Node.js
- JavaScript
- GraphQL API
- Apollo Server

## Installation

To run this project, install it locally using npm:

```
npm install
```

## Usage

After installing npm packages, the application will be invoked by using the following command:

```
npm run develop
```

#### Heroku Deployment

[Click me to see app!](https://book-search-mern.onrender.com/)

- Create heroku app

  ```
  heroku create
  ```

- Create database on MongoDB Atlas:

  ```
  Cluster ➡️ Collections ➡️ Create Database
  ```

- Change Heroku setting

  ```
  Config Vars ➡️ KEY: MONGODB_URI ➡️ VALUE: (from Cluster connect, change password and database name)
  ```

- Git push
  ```
  git push heroku main
  heroku open
  ```

#### App Screenshot

![Screenshot](./client/public/GBS.png)

## License
N/A

## Contribution

Made by Hyunsik kim

## Questions?

Please feel free to contact me if you need any further information:

- [Email](mailto:rlagustlr122@naver.com)
- [Github Profile](https://kayden-hyunsikkim.github.io/React-Portfolio/)
