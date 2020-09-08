# e-commerce-site
A template for an e-commerce site.

Requirements for an E-commerce Site Front End development using HTML, CSS (Bootstrap) and
JavaScript.
This requirement is not exhaustive but serves as preliminary document to identify the scope of work
that needs to done for the website in question.
1. The website is an standard E-commerce Dynamic Site for a company. There is no backend
functionality at the moment but the frontend should be designed with the mindset that it will be
driven to a large extent by a backend service in Asp.net.
2. The Website functionality pages are divided into two major categories Authenticated Access and
Unauthenticated Access. The Authenticated Access is further divided into two main
components Admin Authenticated and Regular User Authenticated.
3. Unauthenticated Access: The following pages are required and can be reached by anyone going
to website, they don’t need to sign in to view these pages.
a. Home Landing page with horizontal dropdown menus, carousel Slider that displays
product images and featured products
b. About us and Contact us page – bear in mind that while the content at the moment can
be static, it should be designed to be populated dynamically
c. Product and product details page – the product page will display image thumbnails of
products and should be able to filter by Category. It should also include pagination if
the number of products exceed the maximum allowed per page. Users should be able
to select from a drop down the number of products to be displayed on a page. When
the product is clicked it should open up to the product detail page where more details of
the product are displayed. The Product should display the thumb nail image of the
product, a short description, price and quantity on hand and if the quantity is 0 then
should display Item out of stock
d. Services pages that display services that are offered and service details pages similar to
Product and Product Details. Only difference is these are not added to a cart but opens
a link to order page.
e. Order and Cart Check out Form to allow a user add products to the cart and then
checkout for payment. (don’t worry about the payment platform). During check out it
should give them the option to check out as guest thereby not requiring a login or as a
registered user where they can either sign up for an account or login to an existing
account and then check out.
f. Customer registration Form:
4. Authenticated Access: Regular Users. These are the pages that users cant access unless the
have an account and are signed in. A function on the front end should check if a user is signed in
if any of these pages are attempted to be accessed and if the user is not signed in should
redirect them to a login page and after sign in take them back to the originating page else they
can access the pages
a. User Profile page
b. User Product Reviews
c. User account page where they can setup their payment methods
d. View Order Statuse. View Past Orders, receipts
5. Authenticated Access: Admin Users. These are pages that only users with admin level access
can access
a. Setup Page that has links to Category Setup, Product Setup, Service Setup
b. Product and Service pages that allows registered products to be updated
c. User Management that displays list of registered users and allows for their management
d. Order Management Page that allows a user to see products that have been purchased
and their various status
e. Report Page that features various dashboards of Charts. _ will discuss more.
These are some of the requirements for now and as the project proceeds, some more requirements will
be enhanced or changed. The most important thing is this is only Front end Design, the back end
processes can be simulated or added statically as long as the design allows for it to be reused for
dynamic updates from a database. The Style Sheets should use BootStrap Framework or similar and if
custom styles are used they should be on separate style sheet and documented. JavaScript should be
used to do all form validations on the frontend and also used for checking authentication once they
have been returned from the backend.
