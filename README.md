# Webpack_from_scratch

check for webpack packages
    "html-loader": "^3.1.0",
    "html-webpack-plugin": "^5.5.0",
    "webpack": "^5.68.0",
    "webpack-cli": "^4.9.2",
    "webpack-dev-server": "^4.7.4"
    
    
At least the above of some version are needed.


webpack.config.js contains two arrays - rules and plugins, you can refer to their repsective detailed configs from internet,
basic is provided in the file


once you have all this setup,
configure two commands in your package.json
- "build": "webpack"
- "start:dev": "webpack-dev-server" // you can name these commands anything


by default build will create a dist folder in your project and will contain the html and js file.


**to run locally you don't need the build command

To run your project
 - npm run start:dev

