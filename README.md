# Nature Scents
## Bring the aroma of nature into your home ✨
<br>
<img src="supporting_docs/design/am-i-responsive.png">
<br>
<br>

### A Full-stack Django-based E-commerce store with products that fill your home with the scents of the natural world, bringing calm, and brightening your day.
<br>
<br>

[]live link
<br>
<br>

## User Experience(UX)

### Strategy Plane
Target Audience:

- People aged 16-55
- Users who like natural scents
- Users who want to improve their home space
- Users interested in health, nature and natural products
- Users who want to regularly receive new products through subscription 

The user can purchase <strong>one off items</strong> on the site, which makes the site useful to anyone who visits looking to purchase a product. The site also offers <strong>product combination bundles</strong> for users who want to try out a range of products, possibly buy as gifts etc. The final option for users is to purchase a <strong>yearly membership</strong> where they will be <strong>'sent a new scent'</strong> every month from the essential oils product section. This yearly subscription keeps the user engaged with the site, and may also lead to further purchases. 

This e-commerce site is a B2C model. The goal of the site is to not only make one off sales but to encourage brand loyalty through subscription and a newsletter. The site uses minimal design, and a no frills up front approach to let the products speak for themselves.

### Strategy Roadmap

|                          Feature                                | Importance | Feasability |
| ---------------------------------------------------------------- | ------ | ----- |
| User can view a list of all products  | 5 | 5
| User can see a detailed view of selected product | 5 | 5
| User can add products to shopping bag and view bag | 5 | 5
| User Account Sign-up and Login | 5 | 5
| User Profile Page | 5 | 4
| User can edit their profile | 5 | 5
| User can delete their profile | 5 | 5
| User can recover a password | 5 | 5
| User can filter products by key word | 4 | 4
| User can purchase products using STRIPE payment | 5 | 5
| User can see reviews from other customers | 3 | 3
| Site owner can add products | 5 | 5
| Site owner can edit a product | 5 | 5
| Site owner can login to admin to edit products/approve users | 5 | 5

### User Stories
------

**Common user stories**:

- As a **user** I want to access the site on all screen sizes **so that I have** a seamless shopping experience
- As a **user** I want to easily understand the site navigation **so that I can** find what I need easily
- As a **user** I want to the site to have no broken links **so that I have** an uninterrupted experience

**Products**
- As a **user** I can filter products **so that I can** narrow down my search
- As a **user** I can view products **so that I can** add them to my shopping bag
- As a **user** I can view a detailed description of a product **so that I can** make a decision about purchasing it
- As a **user** I can select the quantity of a product **so that I can** add required amount to my order

**Basket**
- As a **user** I can add items to my shopping bag **so that I can** create a shopping bag of items to purchase
- As a **user** I can view my shopping bag **so that I can** review my purchase and add/edit as required
- As a **user** I can see a running total in my shopping bag **so that I can** see how much I am spending
- As a **user** I can process a payment **so that I can** pay for my order and receive confirmation

**User Account/Profile**
- As a **user** I am prompted to sign-up for an account **so that I can** benefit from having a profile and selecting a subscription
- As a **user** I can register for an account and login **so that I can** view my order information
- As a **user** I can see if I'm logged in or not **so that I can** login or logout
- As a **user** I can save my default shipping/billing details **so that I can** save time on my next visit
- As a **user** I can sign-up for for a scent subscription  **so that I can** receive new products each month

**Admin**
- As an **admin** I can login to Django administration **so that I can** access the site's backend
- As an **admin** I can add products to the site **so that I can** keep the site up to date and make products available to customers
- As an **admin** I can edit products/create sale items **so that I can** keep the site fresh and offer deals to customers
- As an **admin** I can make custom subscription products **so that I can** attract brand loyalty

**Marketing and SEO**

- As an **admin** I implement SEO keywords and meta tags **so that I can** attract customers and push my site up search engine listings
- As an **admin** I have created a Facebook Business Page **so that I can** increase my customer base
- As a **user** I can sign-up for a newsletter **so that I can** keep in the loop about new products/offers


## Scope Plane
-----------
In order to achieve the goals of the site owner and customer, the following features will be included in this release:

- Landing page with hero image 
- Responsive navbar that will navigate to the various pages throughout the site
- Shop page, that displays all products with the option to filter product category.
- Register/login feature using Django AllAuth so that users can create an account.
- Account page so logged in users can update their details, and see previous orders
- Custom 404 error page

## Structure Plane
-----

**Site flow**

<img src="supporting_docs/flow/guest-user.png">
<br>
<br>
<img src="supporting_docs/flow/authenticated-user.png">
<br>
<br>
<hr>
<br>

**Apps**
<br>

- Home App

- Products App

- Checkout App

- Profile App

- Subscription App

- Shopping Cart App

- Newsletter App


## Skeleton Plane
----------

**Mobile View Wireframes**
<br>
<br>
<img src="supporting_docs/wireframes/homepagemobile.png">
<br>
<br>
<img src="supporting_docs/wireframes/philosophymobile.png">
<br>
<br>
<img src="supporting_docs/wireframes/productpagesmobile.png">
<br>
<br>
<img src="supporting_docs/wireframes/shoppingcartmobile.png">
<br>
<br>
<img src="supporting_docs/wireframes/checkoutmobile.png">
<br>
<br>
<img src="supporting_docs/wireframes/subscriptionmobile.png">
<br>
<br>
<hr>
<br>

**Desktop View Wireframes**
<br>
<br>
<img src="supporting_docs/wireframes/homepagedesktop.png">
<br>
<br>
<img src="supporting_docs/wireframes/philosophydesktop.png">
<br>
<br>
<img src="supporting_docs/wireframes/productpagesdesktop.png">
<br>
<br>
<img src="supporting_docs/wireframes/shoppingcartdesktop.png">
<br>
<br>
<img src="supporting_docs/wireframes/checkoutdesktop.png">
<br>
<br>
<img src="supporting_docs/wireframes/subscriptiondesktop.png">
<br>
<br>

## Surface Plane
-------------

**Colour Scheme**
<br>
<br>
<img src="supporting_docs/design/colourscheme.png">
<br>
<br> 
I have chosen this colour scheme as it is a combination or warm and calming tones which I feel matches the mood of the site, and the products on offer. The pink and orange contrast well with the darker blue and grey tones. 

**Fonts**
<br>
<br>
<img src="supporting_docs/design/fonts.png">
<br>
<br>
I chose Josefin Sans as the main font on the site, as it is simple and clean. I combined this with the Cardo font.
<br>
<br>
<img src="supporting_docs/design/fonts2.png">
<br>
<br>

**Images**
<br>
<br>
All images were found on [Pexels](http://www.pexels.com/)
<br>
<br>
Sources are as follows:
<br>
Photos by Meruyert Gonullu

Photos by Tara Winstead

Photos by MART PRODUCTION

Photoss by Monstera from Pexels 

Photos by Alesia Kozik from Pexels

Photos by EKATERINA BOLOVTSOVA from Pexels

Photo by Dominika Roseclay from Pexels


## Project Planning/Agile
<br>
I have utilised Github's projects section to create a project board with issues in the planning and implementation of the project.

The project board can be found [here] (https://github.com/users/kreilly86/projects/4)
<br>

## Features

### Existing Features
<br>
<br>
- Navigation:
<br>
<strong>Main navigation</strong>
<br>
<br>
<img src="supporting_docs/design/main-nav.png">
<br>
The main navigation is fixed to the top of the page, with a simple logo, a menu, and three icons which link to account functionality, a search bar and the shopping cart. The shop title on the menu bar is a drop down where the user can select what product category to open and browse.
<br>
<br>
<strong>Mobile navigation</strong>
<br>
The mobile navigation containers a burger style menu, which drops down on the left side. 
<br>
<img src="supporting_docs/design/mobile-nav.png">
<br>
When the dropdown menu is clicked, the content is centered and easy to access.
<br>
<img src="supporting_docs/design/navbar-drop-mobile.png">
<br>
<br>

### Future Features
<br>
<br>
In it's current state the project is incomplete. There are still features and functionality to be added which include:

    - A display on the shopping cart icon with the number of products in the shopping cart
    - Custom Django models :
        A model linking products to mood (relaxing, energising, etc)
        A subscription model
        A model for special deals
<br>
<br>
The user is currently able to browse products and add them to their shopping cart. They are then able to click through to the checkout page but this remains incomplete. I also need to make a profile page for users. 
<br>
<br>
The subscrition app is incomplete. Further information needs to be added, and a payment option to charge a yearly one off fee in return for a monthly delivery of custom products for the user.
<br>
<br>
The newsletter sign-up contained in the footer is not functioning yet.

## Marketing and SEO
<br>
<br>

I have created a (Facebook business page)[https://www.facebook.com/nature.scents.irl]
<br>
<br>
<img src="supporting_docs/design/facebook.png">
<br>
Keywords have been used in meta tags based in the base.html file. I have kept the site simple, and didn't overcomplicate this process with lengthy descriptions.
<br>
<br>

## Issues
<br>
<br>
The Django Secret_Key was accidentally pushed to git hub, this has been changed and secured in an env.py file. 
<br>
<br>

### Issue with Stripe Credit card input box when deployed to Heroku
<hr>
<br>
During testing I came up across an issue with the checkout page, specifically the credit/debit card input box. When running locally it was showing up as expected, but on Heroku it was a blank input with no way to input card details. I had various stages of trying to resolve this issue:
<br>




## Testing
<br>
<br>
App Checkout:
<hr>
<br>
As I had not implemented a free delivery threshold, the postage charges generated were quite excessive. e.g. €14. I changed this by creating a free delivery threshold of €50
<br>
<img src="supporting_docs/design/delivery-cost.png">
<br>

### Code Validation
<br>
<br>
- W3C Mark-up Validation
- W3C CSS Validtion
- Lighthouse
- 

## Credits 
<br>
<br>
Code and structure for this e-commerce site has largely come from Code Institute's Boutique Ado walkthrough project: 
<br>
https://github.com/Code-Institute-Solutions/boutique_ado_v1/tree/9ed36dc2c07228041b56b28174dd96ee56e6c59a
<br>

