# Serverless TODO

Hello Udacity Mentor, i have again created the toDo application with a few differences

# Functionality of the application

This application will allow creating/removing/updating/fetching TODO items. Each TODO item can optionally have an attachment image. Each user only has access to TODO items that he/she has created.

# Ordered by oldest first
I have implemented ordering so that the oldest creation date always appears first

# CI/CD 

I have implemented Travis CI configuration so that everytime code is pushed it will run the backend again. This downloads requirements and uses sls deploy using environment variables set in travis CI.

Notes on deployment steps
1. push changes 
2. grab endpoint from travis CI and enter in client config code
3. in client folder run 'npm run start' and app will open


Thank you!!

