---
layout: essay
type: essay
title: "Checkpoint Assignment 3"
# All dates must be YYYY-MM-DD format!
date: 2023-12-12
published: true
labels:
  - MIS
  - Assignment 3
---
<br>
<h1>Show what each page will look like. The pages do not have to be “functional” but the design should clear.</h1>
<p>The index, invoice, login, and registration pages will not change from my previous assignments. The products pages will have at least six products each. They will be divided into Bird pictures, Flower pictures, and Sky picture.</p>
<br>
<h1>Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</h1>
<p>Currently, I have the cart integrated into the products page. Basically, products selected by the customer will be added into a cart that is embedded in their personalized sessionID. When the customer goes to the invoice page, the items selected into the cart will show. For example, if three pictures are purchased from the bird page, and one from both flower and sky page, even after clicking on a different page (i.e. index) the products selected are saved. Then, when the page is changed to invoice.html, all six images will be printed in the form of a reciept.</p>
<br>
<h1>Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</h1>
<p>The products selected stored in shopping cart will be saved to the session. It will store an object of products selected. Other data include the user's cookie. This will be stored in the session so that the user can come back to the page they previously left off on (**This does not exist in my current code).</p>
<br> 
<h1>How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</h1>
<p>I must address invalid user selecting products on my page without logging in. Though I have not completely figured this part out, I believe that this can be addressed using cookies and sessions. Perhaps a cookie could record if the user has logged in or not at any point of their visit, and if they are not logged it, they can not see their invoice. (**May change this solution later). </p>
<br>
<h1>Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)</h1>
<p>Upon successful login, I currently have a personalized inovoice. The name of the user and email is shown on their reciept.</p>
<br>
<h1>If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</h1>
<p>Note: I am not working with a partner.</p>
<br>
<h1>How are you approaching Assignment 3 differently than Assignment 2?</h1>
<p>The biggest difference in approach is the usage of errors and query strings. Instead of relying on errors from the query string, the errors (validation) will be done prior to adding data to the session. Since information will be validated before it is added to the session, I do not need to use the query string for errors anymore. So far, this is what I've noticed, but I'm sure there will be more differences as I begin to finish my Assignment 3.</p>
