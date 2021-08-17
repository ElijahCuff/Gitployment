# Gitployment
Gitployment is a simple project to show how you can add 1 file and a link in your GitHub Project for nearly instant deployment to a test environment.
   
   
- Step 1    
Create a new file in your repo on GitHub called app.json and add your project information like this,
`{ 
  "name": "Gitployment", 
  "description": "PHP powered example.", 
  "repository": "https://github.com/GreyJustice/Gitployment/",   
  "keywords": ["Deployment example", "Deploy to Heroku example project", "test"]
}`
   
    
- Step 2    
Add a button to your repository's READ-ME file, for your user's to utilize the instant deployment functions of Heroku,    

`
Create a FREE account first if you do not yet have one:   
https://signup.heroku.com/    
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)      
`
 
  
  
I use Heroku on my PHP projects.
