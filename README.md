# DBMS2-2023-project
<br>Team members:
<br>200103279 Kabilzhan Aruzhan
<br>210103214 Bissenov Raiymbek
<br>210103061 Kanet Nurgul
<br>210103077 Sabitova Dilnaz
<br>210103453 Nur Bibizaynap


<br>Project Description
<br>This project was implemented using PL/SQL. This is the beginning of a platform that gives people the opportunity to conveniently and comfortably choose the literature they need without leaving home.

<br>Relevance of the topic
<br>In Kazakhstan, the level of informatization and progress in the field of information technology is constantly increasing. To date, especially after Covid, the demand for online shopping services has increased.

<br>Project objective
<br>The purpose of this work is to create an online store for the sale of books on various topics so that people can use it conveniently.


Process of book_shop 

1. The buyer selects a book from the catalog on the store's website

2. Checks for availability of books in the BOOKS table and displays book information such as title, author, price, and publication yeard. 

3. The buyer puts the book in the basket and proceeds to checkout.

4. The system prompts the buyer for shipping and payment information. 

5. The buyer enters such data as first name, last name, delivery address and contact details.

6. The system checks if this data exists in the 'COSTUMERS' table and adds it to the table if it is a new customer. 

7. The system calculates the cost of the order, including the cost of delivery

8. System updates the entry in table 'BOOKS' and reduces the number of available instances by one 

9. The customer receives an order confirmation and information about the date and time of delivery. 

10. After that, the staff will pack the book and prepare the shipment, and then change the "Order_Status"

11. After delivery, the customer can leave feedback in the "FEEDBACKS" table about the book and the purchase process.
