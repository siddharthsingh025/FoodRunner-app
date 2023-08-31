# FoodRunner Andriod app :  :               
### *Done During Internshala Training ( Final Assignment )*
It's a Native  Android Application Written in Kotlin that follow MVC Architecture .Its a food Ordering App that will show you list of restaurants and allows you to add food into your cart and at the end it will generate invoice for you and acknowledgement of success will appeared. Actually , I have  developed this project  during an online 8 week course of InternShala where I used their API for fetching data of restaurant and another API for User Authentication . It's a modular code where different adapters are designed for different Recycler views and separate Models and Functions to handle these model and database are defined .Example :  Order , RestaurantList , FoodItem .Room Database is used for storing data into localSystem of android .Volley library is used for network calls for fetching data and posting data from/to the server (API) .

### what I learned doing this :
1.  Kotlin , XML 
2.  SQLite Database 
3.  API Integration 
4.  Room Database
5.  Recycler View / Adapter implementation 
6.  Coroutine / Multiple threading 

**What You see In it ??**

1. Splash Screen :
      
       A welcome/start page that displays the app logo and disappears after a few seconds.
    ![Screenshot_20220714_211054](https://user-images.githubusercontent.com/87073574/179040277-76885ce8-b046-4078-bda6-f33d61281f26.png)

       
       
2. Login Page :

       The login page is displayed after the welcome/splash page. 
       The user should be able to enter the mobile number and password and click on the Login
       button present below it.
       
  ![Screenshot_20220714_210815](https://user-images.githubusercontent.com/87073574/179041422-be84960d-7b18-4cbc-aae0-0d49960facbb.png)

       
       Clicking on the forgot password text will take the user to the forgot password page while 
       clicking on the registration text will redirect the user to the registration page
       
 
       
       Registration Page : 
       This page contains the following fields namely: Name, Email Address, Mobile Number, Delivery Address, and Password , which users 
       will input and register for the app.
       
  ![Screenshot_20220714_210826](https://user-images.githubusercontent.com/87073574/179049733-6115dd05-0388-4521-8230-d18cc4b02109.png)
       
       
       Forgot Password Page : 
       This page will contain only two fields where the user is requested to enter the mobile number and email address
  
  ![Screenshot_20220714_210840](https://user-images.githubusercontent.com/87073574/179042761-5d6a0102-0158-4ea8-9ce3-170614945e69.png)

       
       
       
       
3. Home Page :

        This would be the page which gets displayed when the user logs in to the application :
        This page would contain the recycler view which contains the list of restaurants.:
        These restaurants will be fetched from an external server by sending a GET request to the  API link given by INTERNSHALA.:
        The result obtained would be an array of JSON objects :->:
        
    ![Screenshot_20220714_210356](https://user-images.githubusercontent.com/87073574/179043309-0e35d005-849e-4a5e-b291-f3b16bce21fa.png)
       
       
4. Navigation Drawer

       Along with the search bar, the navigation drawer is also attached in the home page. The navigation drawer contains the route to different screens
       
    ![Screenshot_20220714_225743](https://user-images.githubusercontent.com/87073574/179047195-2b13e25c-a888-4f4f-99ed-5f567d210c45.png)

       
5. Favorites Page :

       This page will contain the list of the restaurants which were marked as a favorite by you. The favorite restaurants will be saved in the local DB i.e.
       the SQLite database. The database will contain the list of the restaurants saved as favorites and in the favorite fragment, we can directly populateour 
       recycler view with the data from the DB.
     ![Screenshot_20220714_210420](https://user-images.githubusercontent.com/87073574/179047296-9cad791b-8884-4b76-9782-7ae289022926.png)
       
6. Profile Page :

       This page also opens up from the navigation drawer. The page contains the details you entered during the registration for the application.
    ![Screenshot_20220714_210408](https://user-images.githubusercontent.com/87073574/179047702-b24e59d7-1457-45ad-a539-35eff4fdd0e1.png)

       
6. Frequently Asked Question(FAQ) page : 

       This page will contain a static list of questions And  page will contain static data i.e. some questions and answers.
   ![Screenshot_20220714_210332](https://user-images.githubusercontent.com/87073574/179047760-9c227b6b-f6d8-4cf8-9719-fbd780091b26.png)
  
       
6. Some extra Screens Like Food Cart , Order History , Logout DialogBox etc :

 ![Screenshot_20220714_210724](https://user-images.githubusercontent.com/87073574/179048179-a667e9a5-cb0c-4421-af58-19aae99bfbc0.png)
![Screenshot_20220714_210736](https://user-images.githubusercontent.com/87073574/179048194-ad453266-8320-4a06-8fa4-3cb01a9e362a.png)
![Screenshot_20220714_210746](https://user-images.githubusercontent.com/87073574/179048204-73081103-f3c1-40a0-8c08-150f0ba601c4.png)
![Screenshot_20220714_210756](https://user-images.githubusercontent.com/87073574/179048221-27c4d104-74ca-4bdb-a639-22df5c6c7c28.png)
![Screenshot_20220714_210435](https://user-images.githubusercontent.com/87073574/179048242-74f2de26-ece1-439f-963f-92bf65666780.png)
![Screenshot_20220714_210506](https://user-images.githubusercontent.com/87073574/179048250-df8df5f3-5173-48ab-be62-9de40133c51f.png)
![Screenshot_20220714_210447](https://user-images.githubusercontent.com/87073574/179048260-3f57e196-d4c1-47b4-9b36-8fb8e7e47081.png)


       
       
       
   

