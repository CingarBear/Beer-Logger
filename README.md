# Beer Logger
 CPSC 349 Beer Logger Repo

Update: 7/24/2020 @ 13:01:00
- Uploads: Beer-Logger.zip
  - Notable Changes: 
    1. Created a SQL database with a table that contains a username and password for each entry. 
       - There are currently 3 random entries in the database. 
    2. The main page of our project now displays the entries of the database. 
       - This means that our website not has ACCESS to the database. 
       - It is fairly simple to add tables that store data relevent to beer (name, brewery, rating, etc) 
  - Things to consider:
    1. Inside '/php' is a file called 'index.php' which is nearly identical to 'index.html' but the '.php' tag allows us to write HTML code along with PHP code 
       - we need to write php code in order to access entries in our database. 
       - I watched a lot of good videos that helped me get familiar with SQL databases and how to use PHP with them. 
           * Heres a link to the first set of videos I watched: https://www.youtube.com/watch?v=u10xZgNpfCQ
           * NOTE: I started on video #29 and watched until #36 and the rest of my knowledge came from messing around with the code myself. 
    2. I used a program called 'XAMMP' to create the database and it seems pretty important and can be confusing to set it up but once its downloaded, its really easy to use.
      - Heres the link I used to download XAMMP: https://www.apachefriends.org/download.html
        - You might need to change the level of permission that the file has.
           Here are the steps to do it: 
             1. Open your terminal
             2. Change your directory to your 'Downloads' folder
             3. type and tun the command: sudo chmod +x xampp-linux-x64-7.4.8-0-installer.run
             4. type and run the command: ls -al
                  * This command lists the files in the current durectory and displays their level of permission. 
                  * The 'XAMMP' file you downloaded should be hilighted in green now.
             5. type and run the command: sudo ./xampp-linux-x64-7.4.8-0-installer.run
             
 Planned Changes: 
 1. Make it so database has table of beers (name, brewery, sweetness, hoppiness, bitterness, cost?, etc?)
 2. Make it so user can add a beer to the database. 
             
