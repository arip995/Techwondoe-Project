# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)


### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


### Deployment 


#### heroku with heroku git
1.Create an account on heroku
3.Install and login with heroku CLI
2.Create a new project in heroku
4.Connect with heroku repository
5.Push the changes to heroku

### Commands
1.heroku create -a <app-name>
2.git init
3.heroku git:remote -a <app-name>
4.heroku buildpacks:set mars/create-react-app
5.git commit -am "my commit"
6.git push heroku main