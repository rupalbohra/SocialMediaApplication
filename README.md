# Social Media Application - GetSocial

GetSocial is a responsive web application that is built using the MERN stack. On the website, one can easily sign up with their name, email, and password. They can also upload their user profile, location, and occupation. Once logged in, the user can post and can also see the posts uploaded by different users. They can add and remove people from their friends list and can also visit their different profiles on GetSocial. 

Below is the tech stack used in the project:
##Frontend:
React as framework
react router for navigation
FORMIK + yup for form and form validation 
Redux Toolkit for statemanagement
Redux with presistent : to store in local storage
React Dropzone: for image uploads

##Backend:
Node.js : as our runtime
Express.js : as our backend framework
Mongoose for managing our mongo database
Json Web Token (JWT): for authentication
Multer for file uploading


###INSTALLATIONS for the frontend(Client): 
npm i react-redux @reduxjs/toolkit reduxzone dotenv formik -persist react-dropzone dotenv formik yup react-router-dom@6 @mui/material @emotion/react @emotion/styled @mui/icons-material

###INSTALLATIONS for the backend(Server):
npm i express
npm i body-parser   
npm i bcrypt   
npm i cors    
npm i dotenv 
npm i gridfs-stream    
npm i multer multer-gridfs-storage
npm i helmet morgan jsonwebtoken
npm i mongoose
