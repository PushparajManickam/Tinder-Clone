# Tinder-Clone
## Let's come to our tinder-clone
Install package React-App using npx name as "tinder-clone". 

`npx create-react-app tinder-clone`

Now we installed NODE PACKAGE MANAGER.

## Application: There are three section.

    1. Header
    2. Tinder Cards
    3. Swipe Buttons
    
## 1. Header

Install core and icons package from [material-ui](https://material-ui.com/).
```
npm install @material-ui/core
npm install @material-ui/icons
```
We imported PersonIcons, ForumIcon from Icons package and Display the TinderLogo from [1000Logo](https://1000logos.net/wp-content/uploads/2018/07/Tinder-logo.png) website.

## 2. Tinder Cards
  To display person image with name. We used two functions.
  - Swiped
  - outOfFrame
## 3. Swipe Buttons
Import five icon buttons from [material-ui](https://material-ui.com/).
- Replay Icon
- Close Icon
- StarRate Icon
- Favorite Icon
- Flash Icon

## Axios
  Axios is helping HTTP requests to external source.
  Axios Method like GET and POST
  Install the package
  `npm install axios` Axios of BaseURL is localhost:8001
##### Tinder-clone FrontEnd is done. Start NODE PACKAGE MANAGER!!!
```bash
npm start
```

#                                         TINDER-BACKEND
  Install two package from BackEnd
  ```bash
  npm install express
  npm install mongoose
  ```
## Server side script
 There are five sections
 - App config
 - Middlewares
 - DBConfig
 - API EndPoints
 - Listener
 
 ## DataBase Connectivity
Setting MongoDB
    
  > Project Name as Tinder-Clone. then , CREATE CLUSTER.
  > DataBase Access to be set USERNAME and PASSWORD.
  > Network Access in Allow access from anywhere.
  > Connect in connect with your application and then generated databaseURL.

DbCards

  > To store Name and ImageURL into MongoDB.
 
## API EndPoints
 There are two methods in TINDER CARDS.
 - Post
 - Get
 Tinder cards in POST using [POSTMAN](https://www.postman.com/).
  > Copy the hardCode of Name and imgURL in JSON CODE of body raw part and click SEND button.
  > ID is generated successfully.
  
 ## Hopefully understand tinder-clone!!!
