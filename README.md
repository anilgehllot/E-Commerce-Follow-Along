

Milestone 1: Project Overview
Authentication: login logout signup
Product page: Displays all the products
Orders page: Shows orders for each user
Payment gateway
Milestone 2: Backend and Frontend
I created a folder called frontend within which we first created a react file and also installed dependencies and connected the tailwindcss using postCSS. On this folder I created two more folders:

Authorization
Signup
The Authorization folder contains two more folders which are Login and Signup. As part of milestone 2 I was asked to complete the login page which I have completed.

I created a folder called backend which just contains the node modules and I installed express, mongoose, nodemon and cors. 4

Milestone 3: Server and Database
Today I set up a database and a server by using Express and Mongodb-Atlas. I also configured the server to listen on a designated port.
I also created a error handling folder for better debugging.
Milestone 4:
I created a User Model: This is like a blueprint for how your users' data will be stored in the database
I created a User Controlleras well: This will help you manage what happens with your user data (like adding a new user or getting their information).
I also enabled and configured Multer: Multer will allows my app to accept and store files (such as images) uploaded by users.
Milestone 5:
I created a signup page and linked the sign up page to the login page so that it is easy to traverse.
Milestone 6:
I used to JWT token to create an activation for users. This holds basic user information.
Also learnt how to send a URL with the token via email.
I also used nodemailer to send verification emails and created an endpoint to verify the user.
Milestone 7:
I learned to use bcrypt to encrypt the users password and saved the hashed password in the database instead of plain text.
Created a endoint which fetches user data from database on provided emial/username
Validated password by comparing the user’s entered password with the hashed password stored in the database using bcrypt. If they match, proceed with authentication; otherwise, an error is sent.
Milestone 8
Made the card componet
Created a display of all the products with dummy data in Home page.
Milestone 9
Created Product Entry Form
Used form data to send the data over the network call.
MileStone 10
Product Schema
Create end point to wirte the data into DB - Cloudinary and Multer
Milestone 11
Wrote an endpoint to fetch all products from the database and send to client.
Milestone 12
Fetched products from backend using axios
useEffect to load products
Used Card component to display products with details
Milestone 13 (Updation)
Backend: PUT route for updating
Frontend: Page for auto filling the updated data
Milestone 14
Created a handleDelete button
Made a button to delete a singular object
Milestone 15
Added a navbar component
Fixed the cors issue
Milestone 16
Added a Single Page product details
Created Image Modal Component
Milestone 17
Cart Schema
Cart route
Cart Controller [get and addToCart]
Milestone 18
Get Cart Data Route
Milestone 19
Created cart UI
Fetched Cart Details of the User
Milestone 20
Added UI for profile route
Created route for user data
Milestone 21
Created page for the Address city, country, address1, address2, adderss3 and address type.
Wrote the end point for the backend to receive and store it in the backend
Milestone 22
Created a backend endpoint that stores the address inside user profile in database.
Milestone 23
Created a select address page in frontend.
Wrote product schema for the orders in the backend.
Milestone 24
Created a order conformation page in frontend which displays products ordered, address selected and total price details.
Milestone 25
Created a backend endpoint that will help in placing the order.
Milestone 26
Created a backend endpoint that will help getting all the orders of the user.
Milestone 27
Created a frontend page that will display all the user orders.
Milestone 28
Added a cancel button in my-orders and created a backend endpoint for cancel order.
Now user can cancel a placed order.
Milestone 29
Added the razorpay api.
Milestone 30
Continuation of milestone 29.
Implemented online payment using razorpay.
Milestone 31
In store.js file configure an store with userReducer function that will handle global user email state.
Inside userActions.js file write an function called setEmail that will help in storing email state inside global state.
Milestone 32
In Login page we will use Dispatch method to store the mail inside global state
In all the remaining pages acc the mail stored in global state using useSelector
Milestone 33
Created a JWT token.
Created a cookie inside token.
Milestone 34
Extract JWT token from cookie and send to server
Validate JWT token
Miestone 35
Deployed frontend
Deployed Backend

