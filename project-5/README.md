# Serverless TODO

Hello Udacity Mentor, i have again created the toDo application with a few differences

# Functionality of the application

Get - Fetches toDos I have implemented ordering so that the oldest creation date always appears first
Create - creates toDo items
Update - can update details
delete - can delete todos.

# I also implemented CI/CD 

I have implemented Travis CI configuration so that everytime code is pushed it will run the backend again. This downloads requirements and uses sls deploy using environment variables set in travis CI.

# Notes on deployment steps
1. push changes 
2. Then travis will run the steps automatically to sls deploy or you can do manually:
- cd project-5/backend
- npm update --save
- npm audit fix
- sls deploy --verbose --aws-profile serverless
2. grab endpoint from travis CI or manual deployment and enter into apiId in: client -> config
3. in client folder run 'npm run start' and app will open

# Screenshots of successes can be seen in project-5/screenshots


Thank you!!

