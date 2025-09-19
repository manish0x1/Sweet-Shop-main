# The Sweet Shop - [Live Website](https://the-sweet-shop-davidhearl.herokuapp.com)

The live website can be viewed using the link: https://the-sweet-shop-davidhearl.herokuapp.com

## Table of Contents

[User Experience](#user-experience)

[Agile Development](#agile-development-tool)

[Database](#database-design)

[Technologies](#technologies-used)

[Testing](#testing)

[Pass Criteria](#pass-criteria---checklist)

[Business Model](#e-commerce-business-model-and-business-page)

[Bugs](#bugs)

[Newsletter](#newsletter)

[Deployment](#deployment-to-heroku)


## Objective

The Sweet Shop is an e-commerce website that allows users to purchase a selection of confectionary items.
The sweetshop was developed for my 5th portfolio project as part of my Diploma in software development.

## About
The Sweet Shop website provides the user with the ability to purchase a wide variety of sweets.
Upon landing on the site you are greeted with three main options which indicate the purpose of the site.

As a non-logged-in user, you can browse all the products and add them to your bag ready for checkout.
You can then checkout by entering your details along with a valid card. Once your order is complete you will see a confirmation page and a confirmation email will be sent.
As a logged-in user, you will be able to checkout faster as you can save your information to your profile. You will also be able to view your order history and leave reviews on your favourite products.
A logged-in user will also be able to add their favourite sweets to their own page for quick and easy access for repeat purchases.

## User Registration

An important aspect of the site was to give the user an option to purchase items from the site without having to sign up.
Some users can find it frustrating being forced to sign up to a site before a purchase so I felt it was important to avoid this to limit any negative feedback on the site.

## Project Installation Requirements

- pip3 install Django==3.2
- pip3 install django-allauth
- pip3 install Pillow
- pip3 install django-crispy-forms
- pip3 install stripe
- pip3 install django-countries
- pip3 install dj_database_url
- pip3 install psycopg2-binary
- pip3 install gunicorn
- pip3 install boto3
- pip3 install django-storages

## Scope

- A simple intuitive UX experience;
- Easy navigation for the user;
- A site that is visually appealing and responsive across multiple devices

## Structure

- A straightforward and clear layout is present to ensure users can navigate intuitively and have a pleasant experience
- The navbar is fixed to the top of the page to ensure that the user can navigate the depths of the site with a couple of clicks at all time
- The footer is fixed on the bottom of all pages.

## Skeleton


Wireframes created with Balsamiq. The project was then developed from the initial wireframes.

### Home Page
![Home Page](./testing_images/wireframes/home_page_wire.PNG "Home")

### All Products Page
![All Products Page](./testing_images/wireframes/all_products_wire.PNG "All Products")

### Product Detail Page
![Product Detail Page](./testing_images/wireframes/product_detail_wire.PNG "Product Detail")

### Checkout Page
![Checkout Page](./testing_images/wireframes/checkout_wire.PNG "Checkout")

## User Experience


[Back To Top](#table-of-contents)

| Number | User Stories | Met |
|:-:|:----------|:---:|
|1|As a site user I want to be able to easily register for an account so that I can have a personal account and be able to view my profile|[x]|
|2|As a site user I want to be able to easily login and logout of an account so I can access my personal account information|[x]|
|3|As a site user I want to be able to recover my password so that I can still login even if I have forgotten my details|[x]|
|4|As a site user I want to have a personalised profile so that I can view my previous orders and order confirmations|[x]|
|5|As a site user I want to be able to save my personal information so that I can checkout quicker next time I visit the site|[x]|
||||
|6|As a shopper I want to view a list of products so that I can choose items to purchase|[x]|
|7|As a shopper I want to view individual product details so that I can see the product description, price, and rating|[x]|
|8|As a shopper I want to identify deals easily so that I can take advantage of savings on products that I would like to purchase|[x]|
|9|As a shopper I want to see my purchase total at all times so I can keep track of how much I am going to spend|[x]|
|10|As a shopper I want to be able to sort the list of available products so that I can easily find the products with the best rating and best price|[x]|
|11|As a shopper I want to be able to sort for a specific category of product so that I can look for products with the best price and best rating in that category|[x]|
|12|As a shopper I want to be able to sort by price or rating within a specific category so that I can find products easily|[x]|
|13|As a shopper I want to search for a product by name or description so I can find a specific product I would like to purchase|[x]|
|14|As a shopper I want to see what I have searched for and how many results have been returned so I can quickly see if the product I want to purchase is available|[x]|
|15|As a shopper I want to be able to select the quantity when purchasing an item so that I can order more than 1 item|[x]|
|16|As a shopper I want to view the items currently in my bad to summarise my purchases and the cost|[x]|
|17|As a shopper I want to adjust the number of items in my shopping bag so I can easily make changes to my purchases before checkout|[x]|
|18|As a shopper I want to be able to easily enter my payment information so I can have a hassle-free experience|[x]|
|19|As a shopper I want to feel that my personal information is safe so that I can confidently provide the information required to make a purchase|[x]|
|20|As a shopper I want to view and order confirmation after checkout to verify that I haven't made any mistakes|[x]|
|21|As a shopper I want to receive an email confirmation after checkout so I can keep the confirmation of the purchase for my records|[x]|
||||
|22|As a store owner I want to be able to add new items to my store so that I can add newly released products to the store|[x]|
|23|As a store owner I want to be able to edit/update products in my store so that I can adjust prices, descriptions, images and other criteria|[x]|
|24|As a store owner I want to be able to delete a product so that I can remove items that are no longer in stock or are not for sale|[x]|

## Agile Development Tool

[Back To Top](#table-of-contents)

For the agile methodology, I used the GitHub kanban board, it was here where I created the user stories, first as a draft then progressed the items to issues in the to-do column. You can see a snapshot below.

![In progress canban](./media/Canban%20Inprogress.png "Canban")

When I wanted to start working on a feature, I moved the issue from the 'todo' list to the 'in progress list. Once the task was completed it was moved into the completed list.

![Completed Canban](./media/Canban%20Board.png "Canban")

The user stories detailed above are aligned with the project goals. Which was to produce a simple, interactive online store where users could find all types of confectionary items. They would have the ability to select a seemingly infinite combination of sweets and chocolate.

## Database Design

[Back To Top](#table-of-contents)

![Database Schema](./testing_images/database-diagram.PNG "Canban")

## Technologies Used

[Back To Top](#table-of-contents)

### Languages


| Key | Name |
|:-:|:----------:|
|HTML|https://en.wikipedia.org/wiki/HTML5|
|CSS|https://en.wikipedia.org/wiki/CSS|
|Python|https://en.wikipedia.org/wiki/JavaScript|
|JavaScript|https://jquery.com/|
|JQuery|https://en.wikipedia.org/wiki/Python_(programming_language)|
|Markdown|https://en.wikipedia.org/wiki/Markdown|

### Tools, Libraries and Frameworks


| Libraries / Frameworks / Tools | Description | Link |
|:-:|:----------:|:-:|
|Django|Database Driven Framework||
|gunicorn|HTTP Interface Server||
|psycopg2|Database adaptor||
|cloudinary|Image management||
|django allauth|User authentication||
|django crispy forms|Styling forms||
|HTML Validation|Validating HTML|w3.org|
|CSS Validation|Validating CSS|w3.org|
|JS Validation|Validating JS & jQuery|jshint|
|PEP8|Validating python|PEP8|
|Site mockup|Mockup of the site on different screen sizes|https://techsini.com/multi-mockup/index.php|
|Balsamic|Wireframes|Balsamic|
|Visual Studio Code|IDE||
|Bootstrap|Responsive design||
|Font Awesome|Icons||
|Pillow|Image processing tool||
|generateprivacypolicy.com|Privacy Policy Generator||
|Stripe|online payments||

## Testing

[Back To Top](#table-of-contents)

Testing is required on all features, which are outlined and documented in the TESTING.md file which is linked below in this section. All clickable links must be redirected to the correct pages. 
All forms linked to the database must be tested to ensure they post all the correct data.

HTML Code must pass through the [W3C HTML Validator](https://validator.w3.org/#validate_by_uri)

CSS Code must pass through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

JavaScript code must pass through the [JSHint Validator](https://jshint.com/)

Python Code must pass through the [PEP8 Validator](http://pep8online.com/)

Full details on testing can be found here [Testing](./TESTING.md)

## Pass Criteria - Checklist

[Back To Top](#table-of-contents)
| Number | Marking Criteria | Met |
|:-:|:----------|:---:|
|1.1|Implement at least one Django app containing some e-commerce functionality using an online payment processing system (e.g. Stripe). This may be a shopping cart checkout, subscription-based payments or single payments, donations, etc. |[x]|
|1.2|Implement a feedback system that reports successful and unsuccessful purchases to the user, with a helpful message |[x]|
|1.3|Develop and implement a Full-Stack web application built using the Django framework, to incorporate a relational database, an interactive Front-End and multiple apps (an app for each potentially reusable component) |[x]|
|1.4|Implement at least one form, with validation, that allows users to create and edit models in the backend |[x]|
|1.5|Build a Django file structure that is consistent and logical, following the Django conventions. |[x]|
|1.6|Write code that demonstrates characteristics of ‘clean code.’ |[x]|
|1.7|Define application URLs in a consistent manner |[x]|
|1.8|Incorporate the main navigation menu and structured layout |[x]|
|1.9|Demonstrate proficiency in the Python language by including sufficient custom logic in your project |[x]|
|1.10|Write Python code that includes functions with compound statements such as if conditions and loops |[x]|
|1.11|Design a relational database schema with clear relationships between entities |[x]|
|1.12|Create at least THREE original custom Django models. |[x]|
|1.13|All CRUD (create, select/read, update, delete) functionality is implemented. |[x]|
|1.14|Deploy the final version of your code to a hosting platform and test that it matches the development version. |[x]|
|1.15|Ensure that all final deployed code is free of commented-out code and has no broken internal links |[x]|
|1.16|Ensure the security of the deployed version, making sure to not include any passwords in the git repository, that all secret keys are hidden in environment variables or in files that are in .gitignore, and that DEBUG mode is turned off |[x]|
|1.17|Use a git-based version control system for the entire application, generating documentation through regular commits and in the project README. |[x]|
|1.18|Create a project README that is well-structured and written using a consistent markdown format |[x]|
|1.19|Document the complete deployment procedure, including the database, and the testing procedure, in a README file that also explains the application’s purpose and the value that it provides to its users |[x]|
|2.1|Design a Front-End for a full-stack web application that meets accessibility guidelines, follows the principles of UX design, meets its given purpose and provides a set of user interactions |[x]|
|2.2|Document and implement all User Stories within an Agile tool and map them to the project goals |[x]|
|2.3|Design and implement manual or automated test procedures to assess functionality, usability, responsiveness and data management within the entire web application |[x]|
|2.4|Present a clear rationale for the development of the project in the README, demonstrating that it has a clear, well-defined purpose addressing the needs of and user stories for a particular target audience (or multiple related audiences). |[x]|
|2.5|Document the UX design work undertaken for this project, including any wireframes, mockups, diagrams, etc., created as part of the design process and its reasoning. Include diagrams created as part of the design process and demonstrate that these have been followed through to implementation |[x]|
|2.6|Use an Agile tool to manage the planning and implementation of all primary functionality |[x]|
|2.7|Document and implement all User Stories and map them to the project within an Agile tool |[x]|
|3.1|Ensure that all pages on the site can be reached by a link from another findable page. |[x]|
|3.2|Include Meta Description tags in the application HTML |[x]|
|3.3|Include a site title on the parent template |[x]|
|3.4|When defining the relationship between the current document and a linked document, ensure the following: Use “nofollow” for any paid links and distrusted content. Use “sponsored” for any sponsored or compensated links. |[x]|
|3.5|Include a sitemap on your application to allow search engine bot crawling |[x]|
|3.6|Include a robots.txt file to control search engine bot crawling |[x]|
|3.7|Include a 404 response page with an appropriate redirect for attempted access to non-existent content |[x]|
|3.8|Ensure all text content supports the purpose of the application - no Lorem Ipsum text to be used. |[x]|
|4.1|Implement an authentication mechanism, allowing a user to register and log in, addressing a clear reason as to why the users would need to do so. |[x]|
|4.2|Implement login and registration pages that are only available to anonymous users. |[x]|
|4.3|Implement functionality that prevents non-admin users from accessing the data store directly without going through the code |[x]|
|4.4|Apply role-based login and registration functionality |[x]|
|4.5|Ensure the current login state is reflected to the user |[x]|
|4.6|Users should not be permitted to access restricted content or functionality before role-based login |[x]|
|5.1|Create a Facebook Business Page dedicated to your product |[x]|
|5.2|Add a newsletter signup form to your application. |[x]|
|6.1|Document the e-commerce business model underlying your application |[x]|

## E-Commerce Business Model and Business Page


[Back To Top](#table-of-contents)

Facebook: Business Page (https://m.facebook.com/The-Sweet-Shop-111602038303857)

The Sweet Shop Business Model

Our e-commerce business model follows a business-to-business-to-consumer model. 
Everyone loves a sweet treat, and our business aims to provide just that. The Sweet Shop makes satisfying people’s cravings easier than ever. Our business sells wholesale sweets online at an affordable price. We offer a wide range of sweets from old favourites to new flavours. Our website is accessible, easily navigated and provides a quick and simple payment method. 
We aim to be accessible to the mass market and will sell our product via our website with various advertising opportunities including our Facebook page and PPC advertising. 
Below I have included our business model canvas for The Sweet Shop. 

![Business Model](./media/Business_Model.png "Title")

## Newsletter

[Back To Top](#table-of-contents)

The newsletter was created using Mailchimp

Once the user signs up, for the newsletter they show up in the dashboard as can be seen in the example below.

![Newsletter](./media/Mailchimp.png "Newsletter screenshot")

Disclaimer: The address has been blanked out on the image above

## Bugs


[Back To Top](#table-of-contents)

## Known Issues

- Highlighted when creating the unit tests, accessing the product detail page fails for products that do not have images. This is not an issue in production as they cannot physically get to the page from the all-products page. Products that do not have images will also not show up on the home page for non-superusers

## Pylint and Flake8 Errros

- Line errors will occur when lines are deemed to be longer than 79 characters. As a general rule, for all the files I have created, all lines that exceed 79 characters have been shortened unless it has a detrimental effect on readability or causes bugs. In these situations, leniency to 99 characters has been allowed.

## Deployment to Heroku


[Back To Top](#table-of-contents)

This project was deployed with Heroku using the following method:

### Requirements and Procfile

Heroku needs to know which technologies are being used and any requirements the project may have. 
The best way to do this is to create a requirements.txt file.

- In the terminal type: 'pip3 freeze --local > requirements.txt' to create your requirements file.
- Create your Procfile and copy the following code: 'web: gunicorn sweet_shop.wsgi:application' Make sure that there are no blank lines at the end of the file
- Add, Commit then Push these files to your repository

### Creating the Heroku Application

- Login to Heroku
- Select 'Create New App' from within your dashboard
- Choose a name for your application. Note: This name must be unique
- Select the region best suited to you
- Click 'Create App'

### Connecting to GitHub

- From the dashboard, click the 'Deploy' tab
- Scroll down till you find 'Deployment Method' and choose 'GitHub'
- From the search bar, locate your repository
- When you have found your repository, click 'Connect'

### Environment Variables

- Click the 'Settings' tab at the top of the page
- Locate 'Config Vars' and click 'Reveal Config Vars' (This is essentially your env.py file)
- Enter all variables required
    - SECRET_KEY
    - DATABASE_URL
    - USE_AWS
    - AWS_ACCESS_KEY_ID
    - AWS_SECRET_ACCESS_KEY
    - STRIPE_PUBLIC_KEY
    - STRIPE_SECRET_KEY
    - STRIPE_WEBHOOK_KEY
    - EMAIL_ADDRESS
    - EMAIL_PASSWORD

### Postgres Database

- AWS S3 Buckets
- Past Variable into Heroku Config vars

## Acknowledgements

- Code Institute for the default template
- Code Institute's Boutique Ado project for Stripe payments and guidance
- https://mycolor.space to generate gradient background-image
- Code Institute Tutors, General Steer in the right direction when bugs were found
- Focus Group for testing and feedback
#   S w e e t - S h o p - m a i n  
 