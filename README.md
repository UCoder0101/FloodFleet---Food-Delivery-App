# FloodFleet - Food Order & Delivery App

  This Food Delivery App seamlessly connects users with local restaurants, offering a smooth online ordering experience and real-time tracking. Users can browse menus, customize their orders, and select from various secure payment options. With features like restaurant reviews and exclusive promotions, the app enhances the dining experience while supporting local businesses. Contribute to this project to help make food delivery more convenient for everyone! 

 - #### User Application- Just Eat
 - #### Manager Application- Just Eat Chef
 <br/>
 
 | Just Eat                            | Just Eat Chef                       |
 |-------------------------------------|-------------------------------------|
 |<img src="images/0.png" width="250"> | <img src="images/4.png" width="250">|
 
 <br />
 
 
 
 ## 1. Just Eat
 
The main aim of my project was to create a food recommendation system using machine learning model which will be integrated in an android application that will allows users to order food and drinks in a fast and convenient way. Basically, my project consists of three major parts, i.e. 

- Sentimental analysis of feedback given by the customers using RNN.
- Integration of machine learning model in android application.
- Ranking each food item in the menu based on the feedback given by the users. 
<br/>

User application works in 5 stages- 

1. User goes to restaurant, scan QR code at table, select his dishes, make payment and confirm his order.
2. Restaurant manager/chef receives his order and confirms it when his order is server at table.
3. User give his feedback about his individual order.
4. Feedback is analysed by ML model and a score is generated for each dishes based on customer review.
5. Food score of dishes ordered is updated and sorted accordingly in main menu.

<br/>

### Application Workflow - 

|1. Login                                | 2. Scan QR Code                        | 3. Select Food                        | 4. Checkout |
| ---------------------------------------| -------------------------------------- |--------------------------------------|-------------|
| <img src="images/0.png" width="200px"> | <img src="images/12.png" width="200px"> |<img src="images/1.png" width="200px">|<img src="images/2.png" width="200px">|

|5. Payment                              | 6. Order Confirmation         | 7. Give Review                       | 8. Review Result |
| ---------------------------------------| -------------------------------------- |--------------------------------------|-------------|
| <img src="images/3.png" width="200px"> | <img src="images/4.png" width="200px"> |<img src="images/6.png" width="200px">|<img src="images/8.png" width="200px">|

<br/>

Food Score will be updated after each review. Items having maximum food score will be at top and vice versa.

<br/>

 | Max Scored Items                    | Min Scored Items                    |
 |-------------------------------------|-------------------------------------|
 |<img src="images/9.png">             | <img src="images/10.png" >          |
 
 <br/><br/>
 ## 2. Just Eat Chef
 
 This application will be used by Restaurant Manager. They will recieve notification when user places order. Once order is served at table, manager will confirm the order which will enable user to give review of their experience with their food.
 
 <img src="images/4.png">  


### Key Features/Libraries used-
- Payment Gateway - Paytm
- Tflite - RNN Model
- Firebase Authentication
- Firebase Realtime Database
- Firebase Storage
- Glide
- Volley
- QR Code Scanner
- Image Compressor
- Image Cropper
<br/><br/>

