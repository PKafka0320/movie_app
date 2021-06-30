# Movie app

ReactJS fundamentals Course

# Requirements
1. Install nodeJS
2. Install Git
3. Install VSC
4. Open Terminal
5. 'npm install npx -g'

# SETUP
1. Open Terminal
2. Move to directory
3. 'npx create-react-app {directoryName}'

# Start
1. 'npm start'

# Create Git Repository
1. 'git init'
2. Create Repository in GitHub
3. 'git remote add origin {Repository URL}

# Update Git
1. git add .
2. git commit -m "{summary}"
3. git push origin master

# propTypes
1. 'npm i prop-types'
2. import propTypes from "prop-types"

# Install axios
1. 'npm i axios'
2. async fucntion, await axios needed

# Install Router
1. 'npm install react-router-dom'

# Deploying GitHub Page
1. 'npm i gh-pages'
2. add package.json "homepage":"https://{userName}.github.io/{repositoryName}/"
3. 'npm run build'
4. add package.json__scripts "deploy":"gh-pages -d build"
5. add package.json__scripts "predeploy":"npm run build"
6. 'npm run deploy'

# Updating GitHub Page
1. 'npm run deploy'