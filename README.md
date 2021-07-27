# Finder

I wrote this while following Brad Traversy's "React Front to Back" course.

A web application for searching and browsing Github repositories.

Technologies used: React, Context API, Javascript, HTML, CSS.

I have connected this repo to Netlify.  
Open <https://githubfinderxx.netlify.app/> to see the project in production.

## Installation

```sh
npm install
```

In order to use the Github API in development mode you need to supply your own credentials. You can do this by creating a `.env.local` file in the project's root directory and adding the following code:

```sh
REACT_APP_GITHUB_CLIENT_ID='your client id'
REACT_APP_GITHUB_CLIENT_SECRET='your client secret'
```

## Usage

```sh
npm start
```

This runs the application in development mode.
Open <http://localhost:3000> to view it in a browser.
