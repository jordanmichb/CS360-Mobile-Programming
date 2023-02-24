# CS360-Mobile-Programming
<b> About the Project </b>

The client would like an application to be developed that will be used to track items in a warehouse. The application must include an SQLite database to store inventory items and user login information, a screen for logging in/creating a new user, a screen to display inventory, a way to manipulate item details (increase or decrease quantity, delete from database), and a mechanism by which the application will notify the user via SMS when an item quantity has reached zero.

<b> Project Functionality </b>

The user begins at the login page where they can enter their username and password. When clicking "login", the database will be checked for a username and password match. If there is no match, an error message pops up. A user can select "add new user" to add their entered information to the database as a new account. If the provided username is already taken, an error message pops up. Once logged in the user can view their personal inventory as a scrollable list, with the item name, quantity, and unit of measure displayed. An "add item" button opens a new page where an item name, quantity, and unit of measure can be entered. Clicking "add" puts the item into the database to be displayed in the list. If not all fields are filled out, an error message pops up. Clicking on any item in the list opens a new page where the item information is displayed and can be manipulated. Quantity can be incremented/decremented by one by clicking the appropriate button, or a quantity can be manually typed in. The unit of measure can also be changed, and clicking "save" will commit the changes. If the user wants to delete the item they can click the trash icon at the top. Back at the list page, clicking the settings icon will allow the user to toggle SMS notifications. If permission has not yet been given to send SMS messages, the app will ask for permission. If permission is given and the switch is toggled to "on", the user will receive an SMS message when an item quantity has reached zero.

Loggin in: 

![Screen Shot 2023-02-24 at 2 26 53 PM](https://user-images.githubusercontent.com/95947696/221305380-1c660826-c5d5-4c4b-bb99-684bd17db559.png)


Populated Inventory List:

![Screen Shot 2023-02-24 at 2 28 48 PM](https://user-images.githubusercontent.com/95947696/221306004-d459c877-0db6-43bf-8742-0302151c350a.png)

Add New Item Page:

![Screen Shot 2023-02-24 at 2 29 45 PM](https://user-images.githubusercontent.com/95947696/221306276-ff7b28c1-1728-4230-b21d-4cee78a33304.png)

Edit Item Page:

![Screen Shot 2023-02-24 at 2 30 18 PM](https://user-images.githubusercontent.com/95947696/221306469-0c57375c-0d1b-456a-bf87-e6c19aced69e.png)

SMS Settings:

![Screen Shot 2023-02-24 at 2 30 57 PM](https://user-images.githubusercontent.com/95947696/221306747-0678a005-5f00-4b62-88fb-feb78dfe6a24.png)


<br>
<br>

<b> Tools Used </b>

Android Studio
<br>
&emsp;•	Android Studio is the official IDE for the Android operating system and is specifically designed for Android development. 

<br>
<br>

<b> Reproducing the Project </b>

•	Import the project files into Android Studio.
<br>
•	Run the code in the emulator or pair a physical device to use.
<br>
•	Minimum SDK version is 23, and target SDK is 33.
