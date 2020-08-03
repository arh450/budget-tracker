# Budget-Tracker PWA

![badge](https://img.shields.io/badge/license-MIT-blue.svg) ![badge](https://img.shields.io/badge/JavaScript-84%25-yellow) ![badge](https://img.shields.io/badge/HTML-12%25-red) ![badge](https://img.shields.io/badge/CSS-4%25-9cf) ![badge](https://img.shields.io/github/repo-size/gheptig/budget-tracker)

## Heroku URL

https://powerful-shelf-92767.herokuapp.com/

## Brief Description

This is a basic budget-tracker PWA that uses a noSQL database and the Mongoose ORM to allow a user to log deposits and withdrawals with or without an internet connection. When using the application offline the user should see their previously logged transactions, and then when a user brings their connection back online they will be able to see what they logged while they were offline.

## Preview

### Online Transaction

![Preview](https://media.giphy.com/media/SVOHEyWF58tLx01TOr/giphy.gif)

### Offline Transaction

![Preview](https://media.giphy.com/media/YSGrPOokq7gysQrLpx/giphy.gif)

### Back Online Transaction

![Preview](https://media.giphy.com/media/du3vS469sLWb2RcwsP/giphy.gif)

## Technologies Used

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - This website is written in JavaScript and ES6 JavaScript.

- [Node.js](https://nodejs.org/en/about/) - Used to execute code for application on backend and power noSQL database.

- [Express](https://www.npmjs.com/package/express) - Used to route and build API and make requests/responses between database and client.

- [Mongoose](https://mongoosejs.com/) - ORM library used to connect/interact with MongoDB database, model application schema, and execute mongo queries.

- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Used to style the html elements/application.

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - Gives application it's structure and DOM elements.

- [Heroku](https://www.heroku.com/) - Used to host working application. (see app link above).

## Local Installation

After a user clones the repository, they will need to install the NPM packages associated with the application by running `npm install`.

A user can then launch the application by running `node server.js` in their terminal, and access the application at `http://localhost:8080`.

If a user wants to use this application offline they will need to install the application to their device by selecting the `+` in their Google Chrome address bar.

## License

MIT License

Copyright (c) 2020 Augustus Heptig

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contributors/Authors

- Augustus Heptig - Author/Creator
