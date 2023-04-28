---
layout: essay
type: essay
title: "E6: Reflecting on Assignment 3"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Assignment 3 
---
Develop a prototype of your entire application that addresses the following points: 
Show what each page will look like. The pages do not have to be “functional” but the design should clear. <br>
**A link to my powerpoint <href= https://youtu.be/nlB7gV0zd30> can be found here.**  

Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart. <br>
**The design for site shopping cart will be a separate page displaying the quantity ordered for specific products and the price of each. Subtotal and total will be shown as well. If the user chooses to edit their information, a button will be allowed to go back to the products display page. This will work on the site by having users click the purchase button which will then redirect users to the log-in page if they did not sign in. If they did, then it will automatically forward them to the shopping cart page, where they can decide to check out which will then lead to the invoice page.**  

Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session. <br> 
**Sessions will be used to manage my cart by saving the quantities ordered in the server. In addition, it will also hold the session id so that users who are logged in will be able to have a unique session id to access their cart. The session will be storing their product type key which will be stored in an array format. Some examples of this are:  {Funko_Pop: [1.2.3] Everybody: [4,5,6].**

How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address.<BR>
**Access will be avoided when the user has not logged in by bouncing back if an acceptable cookie is not found. The user will then be bounced back to the log-in page where they can log-in which will give them a cookie. The particular security concern is hacking the cookie to access the application. Users are able to modify the cookie and therefore hack the cookie.**

Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)<br>
**Upon successful login, we will display user’s name, email, and log in count & time. In addition, a confirmation email will be sent back to the user.  
We will do this by displaying the user’s name throughout all the pages. On the invoice page, the user will have their name, email, log in count and time display. I currently have the invoice page working, however, need to implement the always displaying username interface.**  

If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when? <br>
**N/A**

How are you approaching Assignment 3 differently than Assignment 2? <br>
**I am approaching assignment 3 differently by starting early and spending more time conceptually first rather than coding and troubleshooting.**  

 

 
