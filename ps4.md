# mat301-PS-4.md
 1.) Create three tables: Customers, Orders, and OrderItems. 
 I did this but to show I need to have MS access granted for you to see.
 2.) Why do we need an OrderItems table? 
 We need an order items table because one person man buy more than one item. 
 3.) Create linked tables in MS Access.    
 I did this but to show I need to have MS access granted for you to see.
 4.) Create forms to enter customer data.  
 I did this but to show I need to have MS access granted for you to see. 
 5.) Create a form with a subform to enter orders and order item.     
 I did this but to show I need to have MS access granted for you to see. 
 6.) Use forms created in 4 and 5 to insert Customers and Orders.        
 Add customers that have not made any orders. Make the number of entries relatively small. Why?     
 I did this but to show I need to have MS access granted for you to see;    
 you don't want to make too many entries because that is very time consuming;     
 often programs are created for entering a large volume of information.  
 7.) INSERT into unemath_Carbone.Customers (customer_id, customer_first, customer_last, customer_email, customer_tele)VALUES ()   
 INSERT into unemath_Carbone.Order (order_id, customer_id, date, order_total) VALULES ()   
 INSERT into unemath_Carbone.OrderItems (orderitem_id, product_id, quantity, price) VALUES ()  
 8.)Find all customer orders.      
 SELECT * FROM unemath_Carbone.Orders;  
 9.)Select all customers that orders a certain product (This will depend on what data you entered into the table).      
 Find all customers that ordered product 3452.        
 SELECT * FROM unemath_Carbone.OrderItems WHERE product_id=3452; 
 10.) List 5 questions that you can answer from this data.        
 1.) Select all customers that had a zip code of 01966.        
 2.) Count all customers that had order totals greater than 100 $.       
 3.) Count all customers that ordered more than one item.      
 4.) Count all customers that had zip code of 01930.     
 5.) Select all customers that spent more than 50 and less than 100$.
