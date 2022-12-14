# Capsone-Build-Your-Gym-Ecommerce
I created an ecommerce website where users can register an account and purchase gym products. The backend was created in the Spring Boot framework written in Java, whereas the front end was created in the React framework written in JavaScript.

# Home Page
Here is the homepage of Build Your Gym. It features a list of items separated into categories the user can view and add to their cart.

![image](https://user-images.githubusercontent.com/62003762/207675083-da747797-5b74-4f25-a3bb-a5609ab6708f.png)

# Register Page
Users can register an account that will be stored in the MySQL database. The user's ID and information will then be saved on their web browser through a JSON Web Token.

![image](https://user-images.githubusercontent.com/62003762/207675553-c16088d2-c863-473b-8e23-41465d053b61.png)

# Checkout Page
Here is the Checkout Page. After a user adds gym equipment to their cart, they can view their items. They can select a quantity for each product, which will calculate the new quantity with the original price of the selected product, and a new total amount will be generated.

![image](https://user-images.githubusercontent.com/62003762/207676446-94517d19-e9c5-46b4-b23b-11c448dfa26b.png)

# Flowchart
Here is an example of a flowchart I created showing the process of a user logging into their account.
![image](https://user-images.githubusercontent.com/62003762/211480994-170b31a2-a8c4-4ca1-b21f-c615b2bb6020.png)

# Physical Solution Design
![image](https://user-images.githubusercontent.com/62003762/211481165-1f1b004a-9d36-46fb-bbbf-f294b9c58788.png)

# Logical Solution Design
![image](https://user-images.githubusercontent.com/62003762/211481219-1c970d86-fe9b-4539-8a3a-72a78dd8e65f.png)

# Architecture of the Solution
This shows the architectural solution of the project. Users will view and interact with the React application as it implements front end features. The React application is communicating with the back end Spring Boot application with its REST APIs. Data pertaining to users and gym products are stored to the MySQL databsae.
![image](https://user-images.githubusercontent.com/62003762/211482844-5990ea14-7409-4eb2-b727-c0e46c9ecd47.png)
