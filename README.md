# FoodRunner Andriod app :  :               
### *Done During Internshala Training ( Final Assigment )*
## Its a food ordering app Model :         using Kotlin , XML , SQLite  Database , API provided by Internshala .

### In this Project I have learned about the following topics listed below: 
 
   >1. Different types of Layouts
   >2. Various widgets
   >3. Intents and Shared Preferences
   >4. Navigation drawer
   >5. Fragments
   >6. Recycler View
   >7. Fetching/Sending data from/to Internet
   >8. SQLite Database
   >9.Fetch the JSON data from the server
>

**What You see In it ??**

1. Splash Screen :
      
       A welcome/start page that displays the app logo and disappears after a few seconds.
       
       
2. Login Page :

       The login page is displayed after the welcome/splash page. 
       The user should be able to enter the mobile number and password and click on the Login
       button present below it.
       
       Clicking on the forgot password text will take the user to the forgot password page while 
       clicking on the registration text will redirect the user to the registration page
       link2
       
       Registration Page : 
       This page contains the following fields namely: Name, Email Address, Mobile Number, Delivery Address, and Password , which users 
       will input and register for the app.
       link3
       
       
       Forgot Password Page : 
       This page will contain only two fields where the user is requested to enter the mobile number and email address
       link4
       
       
       
       
3. Home Page :

        This would be the page which gets displayed when the user logs in to the application :
        This page would contain the recycler view which contains the list of restaurants.:
        These restaurants will be fetched from an external server by sending a GET request to the  API link given by INTERNSHALA.:
        The result obtained would be an array of JSON objects :->:
       link5
       
       
4. Navigation Drawer

       Along with the search bar, the navigation drawer is also attached in the home page. The navigation drawer contains the route to different screens
       link6
       
5. Favorites Page :

       This page will contain the list of the restaurants which were marked as a favorite by you. The favorite restaurants will be saved in the local DB i.e.
       the SQLite database. The database will contain the list of the restaurants saved as favorites and in the favorite fragment, we can directly populateour 
       recycler view with the data from the DB.
       link7
       
6. Profile Page :

       This page also opens up from the navigation drawer. The page contains the details you entered during the registration for the application.
       link8
       
6. Frequently Asked Question(FAQ) page : 

       This page will contain a static list of questions And  page will contain static data i.e. some questions and answers.
       link9
       
6. Some extra Screens Like Food Cart , Order History , Logout DialogBox etc :

     link 10-14      
       
       
       
   

