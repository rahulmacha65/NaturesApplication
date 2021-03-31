# Natures Applications

The Natures Application consists of nine tours in different cities where you can book those Tours based on Reviews, Ratings and some Photos of the Tour.
You can also see Map of your Tour and It will display some model to travel that Tour like on day1 certain place based on the duration of your Tour.

##  Modules used:

- Stripe module: 
  - Used as a Payment Gateway 
- SendGrid :
  - It is for sending the mail to the User after a successful booking.
- sharp module:
  - To resize the images 
- multer module:
  - To upload multipart/form-data its primarily used for photo or file uploadings
- axios module:
  - It is to make Promise based request.
 
- Mapbox module:
   -It is to add the Map on the Tour page and it also located by Point on that there was a popup to locate that 
   
-pug module:
  -It is a Templet Engine that is used to create Templets.
  
-nodemailer module: 
  -It is popular for email operation and checking mails on mailTrap in development
  
-crypto module:
  -It is default module in node.js which is used to Encryption of token.
  
-JWT module:
  -It is used to generate the JWT token where we can verify whether the user is authenticated or not it will be stored in a cookie
  
-bycrptjs module:
  -we used to encrypt the password and store that encrypted password in DB.
  
##  MongoDB Tools Used:

-comapss:
  -we can see all the document and we also edit those document in this tool.
  
-Atlas:
  -It is used to strore our Data in the Cloud.

##  Other Modules Used:

-file system module:
  -It is used to read/write files sync and async
  
-http module:
  -Used to create a server
  
-url module:
  -To access the url
  
-slugify module:
  -It is present in API after the Domain name like **naturesapp.com/tours** here tours is slug url
  
-Nodemon:
  -It is used to run our server every time when we save the file.
  
-static middleware:
  -It is used to access the data which is not accessed by the Routes.
  
-cookie-parser Module:
  -To send the token in cookie to prevent Cross-site Scripting Attack
  
-Express-rate-limit module:
  -It used to limit the requests which prevent BruteForce Attack.
  
-Express-mongo-sanitize module:
  -It is to prevent the NoSql Injection Attack.



