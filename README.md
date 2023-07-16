# OnlineBook-Store
Online Book Store Project is a web-based application in Java, 
developed mainly for bookstores and shops to computerize the book purchasing process. 
This project aims at creating an efficient and reliable online book selling and buying platform. 
After the implementation , one can inquire and buy any book available in the store from anywhere.


        𝕆𝕟𝕝𝕚𝕟𝕖 𝔹𝕠𝕠𝕜 𝕊𝕥𝕠𝕣𝕖 𝕛𝕒𝕧𝕒 𝕡𝕣𝕠𝕛𝕖𝕔𝕥
          Online book store is a web application to allow users to select books through internet and get
            them delivered to their doorsteps

            It allows registered users to do the following:
 Login
 Borwser and query books based on price, title, and category
 Add books to shopping cart.
 Update quantity in shopping cart
 Remove books from shopping cart
 Finalize order for books in shopping cart
 See the status of orders placed in the past - orders history.
 Cancel an order, if status of the order is new

  The following table lists operations and associated objects and files.
  Operation                     Files Associated         Objects
  Login                         login.html, login.jsp     User javabean
  Home Page                      home.jsp                 User JavaBean,   CartJavaBean
  - Displays shopping cart
  Updation of user profile and    changeprofile.jsp       User JavaBean
password
Logging out                     logout.jsp               User JavaBean
Browsing available books.       browsebooks.jsp           none
Querying books on price,        querybooks.jsp             none
title and category
Adding a books to Shopping cart   addbook.jsp             User Bean,Cart Bean
Finalizing Order                 home.jsp                 User Bean,Cart Bean, Order EJB
Displaying previous-Orders History     ordershistory.jsp       User Bean
Displaying items of an Order           orderitems.jsp         User Bean
Cancelling an Order                   deleteorder.jsp,orderitems.jsp  User Bean,Cart Bean, Order
EJB 
