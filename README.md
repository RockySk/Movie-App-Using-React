# Movie Review App

This is a simple web application that displays a list of movies along with their details such as title, year, and poster image. The application is built using React.js and bootstrapped with Create React App.

Getting Started
To run the application on your local machine, follow these steps:

Clone this repository to your local machine
Install dependencies by running npm install
Start the development server by running npm start
Open http://localhost:3000 to view the app in your browser
Usage
The app displays a list of movies retrieved from a JSON file. The movie details are displayed using the Movie component, which receives the movie data as props. The Header component displays a simple header for the app.

Code Example
Here is an example of the App component that renders the Header and Movie components:

jsx
Copy code
import "./App.css";
import Header from "./Components/Header";
import Movie from "./Components/Movie";
import movies from "../src/Components/movie.json";

function App() {
return (

<div className="App">
<Header />
<div className="main">
{movies.map((element, index) => {
return (
<Movie
              key={index}
              title={element.Title}
              year={element.Year}
              img={element.Poster}
            />
);
})}
</div>
</div>
);
}

export default App;

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

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

![output1](https://user-images.githubusercontent.com/79098477/230895740-fb301519-e0b5-44f5-be6b-3f1b571ab7e5.png)
![output2](https://user-images.githubusercontent.com/79098477/230895821-0d288911-158d-4836-8b58-fadba3d7b8d3.png)
![output3](https://user-images.githubusercontent.com/79098477/230895903-35c7ff96-277a-4fca-b1ec-427279acf83c.png)
Screenshot of Project

![output4](https://user-images.githubusercontent.com/79098477/230895671-15cc5ea6-aa8a-4a5f-894e-94d5bbff64c3.png)


