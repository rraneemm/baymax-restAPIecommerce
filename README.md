# baymax-restAPIecommerce
This is the very first  REST API project to come to life.
Having this be the first ever to launch - it truly looks like beginners tracks and hopefully that should change with time.

Contents of the ZIPPED folder:
- app.js 
- package and package-lock (json)
- routes folder
--> site
- relations folder
--> index
- models
--> User
-->Product 
--> Order
--> Cart 
--> CartItem
--> OrderItem 
-db
--> datbase
-author
--> sites 

HOW TO USE: 
Extract the file onto your machine and open it via your IDE 
To test/work with it make sure you have access to database server
Use postman to try the available options: 
- log in as a user
- sign up as a user 
- add,delete,search for products 
- create an order

You might find plenty of missing options like checking if the signed up user is already in the database- consider it a task and do it yourself! 

AN ILLUSTRATIVE GUIDE: 
![Untitled](https://user-images.githubusercontent.com/110533689/188289851-70eaa771-ccc1-44f0-ae9f-6b6ec599eeac.png)

This is how the postman UI should look like- the black arrow is where you will typ ethe URL with the required redirectories, the maroon arrow is where you will type what we can call is the input which will be depending on the code so look in the modules for how to write each object aka what is required from it(note it is all JSON format), finally the blue arrow is where you will be recieving (hopefully) he required response.
This example shows how you can add a product through locaolhost:8080/shop/add-product which will then return an object with all the information. 



