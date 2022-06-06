# branchOut

### Group Project

## Overview

Not sure what movie to watch tonight? Want to find out if it's any good? You need to visit Rancid Tomatillos!

The Rancid Tomatillos Web App, built in React, displays some of the newest films out there! Rancid Tomatillos features an easy to use interface that shows the movie rating on any movie poster. Once hovering over a movie poster the movie title and release year are available as well. If you then click a movie poster a movie synopsis/overview is available about the film along with additional movie details like genre and even a Trailer of the film!

### [branchOut Deploy Link](https://joshmallery.github.io/rancid-tomatillos/)

## Project Views

### Home View with Dashboard Page:
![Dashboard](https://user-images.githubusercontent.com/3982238/169899057-16d84903-e0cb-4a3c-a8e0-31145701daaa.gif)

### View a Course and Lesson:


### Add a Form:
![Add Form](https://user-images.githubusercontent.com/3982238/169899014-003c0582-8871-48b5-8aa6-7e45e3deeed4.gif)

## React

- This multi page App with React was an exercise for us to learn and grow our knowledge of the framework.
- React Router was implemented to give unique URLs to the movies as well as default URL handling. Rancid Tomatillos shed light on how a multi page app might work with unique URLS in the real-world.
- Compared to previous projects in VanillaJS, React maintained a sync'd state at all times, which expedited the process of displaying information accurately.

## Cypress Testing

- All Testing of User views and user interactions
- Error Handling of Server errors and invalid URLS Tested
- Fetch requests are stubbed

![Cypress Testing](https://user-images.githubusercontent.com/3982238/169899087-0525d4a8-f9f7-4d86-ab7a-bac70edd99a8.gif)

## Local Set-Up Instructions

- From the repo click the code button and copy the SSH link.
- Open terminal by pressing command + space bar, and search for terminal
- Inside of your terminal type `git clone` and then paste the ssh link. It should look like this: [git@github.com:JoshMallery/BranchOut.git](git@github.com:JoshMallery/BranchOut.git)
- In your terminal type `cd branchOut`
- Type `npm install`
- Do not run `npm audit fix --force`
- Then type `npm start` This runs the app in the development mode.
- Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
- The browser should then deploy using a local host
- Enjoy using branchOut!

- NOTE: Make sure that you type `Control + C` in your terminal when you are done using the application. This ensure the server will stop running before your close your Terminal.

## Instructions for Use

- On opening the browser, a user is free to scroll the current courses that exist!
- A user can hover over a movie poster for title and release year.
- A user can click a movie poster and get additional movie details including a trailer to help them make their decision on what to watch.
- A user can also search for a movie title in the search bar and click on the results.

## Technologies Used

- React
- React Router
- ES6 JavaScript
- CSS
- HTML
- Fetch Web API
- Cypress Testing
- GET requests
- POST requests
- Delete requests

## Future Features

- User Login Page for Teachers or Students
- Teacher and Student User Permissions, Student - read-only access

## Project management

- We used a [Github Project Board](https://github.com/JoshMallery/BranchOut/projects/1) stay on task and meet the deadlines.

### Figma WireFrame
![DashboardView](https://user-images.githubusercontent.com/96563007/172260248-35226b8f-aee1-4b84-84eb-6a80c3ea589f.png)

![LessonView](https://user-images.githubusercontent.com/96563007/172260380-1f6bcde7-ddba-460b-a902-906adc0512f2.png)


### Figma Component Architecture

![Data Structure](https://user-images.githubusercontent.com/96563007/172260578-13a529f1-48ab-436f-870b-bb63c76fa7e3.png)

## Contributors

- [Josh Mallery](https://github.com/JoshMallery)
- [Tyler Tedesco](https://github.com/sted1994)
- [Whitney Perricone](https://github.com/Wperricone)

## Image Credit

- branchOut logo created by [Freelogodesign.org](https://www.freelogodesign.org/)

------------------------------------

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
