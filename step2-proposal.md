# Capstone 2

## Project Proposal

### 1 - What tech stack will you use for your final project?

-   Node/Express/React

### 2 - Is the front-end UI or the back-end going to be the focus of your project? Or are you going to make an evenly focused full-stack application?

-   Evenly focused full-stack application.

### 3 - Will this be a website? A mobile app? Something else?

-   This will be a website, but it will be fully responsive for mobile and tablet devices.

### 4 - What goal will your project be designed to achieve?

-   Create a visually appealing art porfolio / mural business webiste with an e-commerce store, and potentially a custom CMS for the admin.

### 5 - What kind of users will visit your app? In other words, what is the demographic of your users?

-   Potential mural clients, people who like art, and people who would like to buy art.

### 6 - What data do you plan on using? How are you planning on collecting your data? You may have no picked your actual API yet, which is fine, just outline what kind of data you would like it to contain. You are welcome to create your own API and populate it with data. If you are using a Python/Flask stack are required to create your own API.

-   I plan on using the Stripe API, and potentially a CDN as well, depending on what the best option for hosting/displaying images will be.

### 7 - In brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). Answer questions like the ones below, but feel free to add more information:

> a. What does the database schema look like?
>
> -   Admin table, Posts table (for posts created through the CMS), Inventory table (for the store), Transactions table (for the store), Email list Table, Customer info Table.
>
> b. What kinds of issues might you run into with your API? This is especially important if you are creating your own API, web scraping produces notoriously messy data.
>
> -   Stripe has very good docs, so I don't anticipate running in to issues with the API itself, but rather with my implementation of it, if anything.
>
> c. Is there any sensitive information you need to secure?
>
> -   Customer information (ie- shipping address), Admin password, potentially anything that Stripe requires I store on my end.
>
> d. What functionality will your app include?
>
> -   Navigation through the portfolio and projects, an e-commerce store to buy art pieces/prints, Admin authentication, Admin ability to add posts.
>
> e. What will the user flow look like?
>
> -   User flows will be fully documented in a separate file, but include: - Browsing Murals - Browsing General Art - Shopping - Checking Out & Result - Contact - Admin Login - Admin View Store Information/Analytics - Admin Store Item CRUD - Admin Post CRUD - Admin Logout
>     f. What features make your site more than a CRUD app? What are your stretch goals?
> -   Admin authentication, E-commerce
