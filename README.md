# Intern-Project-Video
OOBE video
Cannot share codes due to the privacy statement, but since it's a project with over a million registered product users worldwide, I'll just share a simple demo of the react prototype finished by myself during the internship. 

# What I did?
•	Move the existing OOBE Service from JQuery to React.js, constructed frontend with React.js, Redux and gulp.

•	Finished Breadcrub navigation and page transition animation, manually realized all the transition animation effect.

•	Used middleware Redux-thunk to deal with complex synchronous and asynchronous request like Ajax request. 

•	Finished the international locale function, and solved network connection problems through adding proxy;

•	Improve the batch insert time of redemption 100,000 codes from 2 days to 45 second in Sku Central Server(Node.js)


# Out of the Box experience (OOBE) application；
Provides various features for the end user who has purchased a product by providing:

1. Product Registration
2. Software Download Specific to the Product, and OS
3. Link to Knowledge Base Articles
4. Redeeming Product Offers if any etc. 

# Move it from JQuery to React.js
Existing OOBE Application is using JQuery, we want to move it to React.js;

# Why React?
Decision to adopt React was influenced by a number of factors, most notably: 
1. startup speed
2. runtime performance
3. modularity.

Lightweight, fast and modern way to execute code.

Not only web, but also mobile apps...(Both iOS and Android)

React Native is a native version of React and its main purpose is to bring the power of React to native mobile apps development.

# Description
When the user connect their new drive to computer, the sign-up page will pop up to the user. 
We’ll automatically detect the info of drive, like series number, product model,color, and so on. 
Then we send the HTTP request to the server to get info back. 
All these info on OOBE are real-time info from the server.
We can also detect the version of OS, the local language setting, and apply these info to OOBE.
Before rendering the sign-up page, we'll check if this drive has already be registered; if it does, we'll get the user info from the server and show them as default value, so that users don't need to input these info again.

# Video link
https://youtu.be/O7aA91zMjl0
