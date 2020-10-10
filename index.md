# Overview
The Project's backend is realized using Spring Boot and for the frontend Vue is used. Project purpose is to create a fully functional eBooks store.

# Part 1
In the first part the most important functionality of the eBooks store has been implemented. Currently one user account functions as an admin and client, as security will be added in the third part. 

The eBooks webpage scales based on screen size to make using the site comfortable on both desktop and mobile devices.

The eBook store application displays all books that are currently available for purchase and it is possible to see detailed descriptions of each book individually. It is possible to search for books by ISBN, title, author and keyword. Books can be sorted by price (ascending, descending) and by genre.

As it is a web store that sells eBooks, user can add products to his shopping cart. User can see the contents of his cart. Also if needed it is possible to remove items from the cart. When all necessary products have been added to the cart, the order can be placed and a confirmation about it will be displayed to the user.

Website admins can manage the books. They are able to add, see, edit and remove books.


# Part 3
In the third part logging in from different accounts will be implemented. There will be three different user roles: guest, user and admin.

Guests can see all books and their detailed descriptions. In addition to that, guests are able to sort books by price, genre and in alphabetical order; search for books by ISBN, title, author and keyword. Guests can create an account for themselves to become a user or log in to an existing one.

Users can do all the things that a guest can, but they have additional possible activities. Each user has their own personal shopping cart in which they can add products. Users can see their shopping carts contents and remove items from there. Users can finalize their order by submitting it. Users have their personal wishlists, where they can add books that they would like to save for future references.

Admin role is the most powerful one. Admins can add, see, edit and remove books. In addition to that, admins can also see all registered users accounts and delete them if necessary.

Links
Backend repository: https://gitlab.cs.ttu.ee/rakulb/iti0203-2020-backend-team11-bookstore
Frontend repository: https://gitlab.cs.ttu.ee/rakulb/bookstore-11-front

# User stories
- As a guest I can use a beautiful, logical and homogeneous application.

- As a guest I can see all books and their detailed descriptions.

- As a guest I can search for books by title, author, keyword and ISBN.

- As a guest I can sort books by price.

- As a guest I can see books displayed by genre.

- As a guest I can create an account.

- As a guest I can login to an existing account.
 
- As a user I can do all the things that guests can do. 

- As a user I can add products to the shopping cart and see confirmation that it was successful.

- As a user I can see the content of my cart and remove unwanted items from there.

- As a user I can place the order and see a confirmation that my purchase was successful.

- As an admin I can see, add, remove and edit books.

- As an admin I can see registered users and delete their accounts.

- As an admin and user I can log out from my account.

# Database schema

![db](https://user-images.githubusercontent.com/47223643/95575904-3810bf00-0a38-11eb-8e9e-640b0be20675.png)

# Architecture drawing

![architecture_drawing](https://user-images.githubusercontent.com/47223643/95659238-4dfdad00-0b28-11eb-90f2-e9b216ea3e5e.png)

#TODO:
## Technical description
TODO
Technical description. Technical descriptions are good inside tenders. You have to describe it well and professionally. Write about components, protocols, technical details, data tables, etc. Add description to wiki.
