
# P5-ECOMMERCE

A Django project composed of multiple apps. The project uses both Front End and Back End Development skills.

A simple beauty based ecommerce site where customers can view and sort, filter products on the website, register, add products to the shopping cart, edit shopping cart, buy products and view orders on their account. 

To begin with, I used the accounts app from the Django Authorization tutorial
Then build a products app with a model to showcase items that are retailing.
Then create a shopping cart which works in the current session and a checkout app.

## UX
 
The site has a minimalism look very few colours incoporated so that emphasis can go to the product. I want the user to be less distracted and focus on the task at hand which is shopping.
 
## Features
search app - allows user to make a search on website

cart app - to add products to the cart or update them in the cart

accounts app -  has customized user model. It accepts email as a username
 
### Existing Features
The Products App- renders products which are in stock to be viewed on page

The models
Checkout uses one model, to show the product name, description, price and image.
The Views
Our view returns everything from the products model to the products.html

Login - allows users to login by completing a form
Register - allows users to register by completing a form
Logout - allows users to logout by clicking a button



## Technologies Used

Python3

Django

Stripe - to process payments

AWS- to host static files

HTML5

CSS3

JavaScript

Bootstrap


## Testing

manual testing by creating a user and going through all the functionality of the website. I also tested the website on different screen sizes. 

## Deployment

Deployed to Heroku
Deployed to github

## Credits
Code Institute ecommerce miniproject

### Media
- The photos used in this site were obtained from pixabay

### Acknowledgements

Code Institute ecommerce miniproject
