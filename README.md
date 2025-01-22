# Hackathon Report: Marketplace Builder (eCommerce Website Development)
**Event Overview:
Duration: 7 Days
Event Focus:** Developing an eCommerce website from scratch, covering the process from initial planning, building features, and deploying to a staging environment.
# Day 1: Marketplace Builder - eCommerce Website Development


**Objective:** Kickstart the project by designing the architecture of the eCommerce website, planning features, and setting up development environments.


**Key Activities:


Project Kickoff:**

Introduced the concept of building an eCommerce platform from scratch, focusing on creating an intuitive, scalable marketplace for users to buy and sell products.
Discussed the business requirements, user needs, and essential features for the platform, such as product listings, user authentication, shopping cart, checkout process, and order management.


** Planning:**

Created a detailed project roadmap and identified deadlines for each milestone.


**Designing the Database:**

Instead of a traditional relational database, we chose Sanity as the backend content management system (CMS) for managing product and user data. Sanity's flexible content model allowed us to create structured content types for products, categories, and user profiles.
Frontend & UI/UX Design:

Designed the user interface layout for the eCommerce platform, ensuring that it was clean, user-friendly, and mobile-responsive.
Focused on creating a modern, visually appealing design that would improve the customer shopping experience.


**Technology Stack Decision:**


**Chose technologies to build the eCommerce platform:**

Frontend: React.js (for a dynamic, interactive UI)
Backend (CMS): Sanity.io (for content management, providing a headless CMS for product listings and user profiles)
Authentication: JWT (for secure user login and registration)
Deployment: Vercel (for frontend deployment), Sanity Studio (for backend content management interface)
Development Environment Setup:

Configured development environments using GitHub for version control.
Installed necessary dependencies and frameworks (Next.Js, Sanity client) for backend integration and frontend development.

# Day 2-5: Progress on Building Features and Integrations

**Key Activities:**

**Frontend Development:** Built key components such as the homepage, product listing page, product detail page, and cart page.

**Backend Development with Sanity:** Set up Sanity as the CMS to manage product data, categories, and stock quantities. Created structured content schemas in Sanity Studio for easy product management.
Example schema for a product included fields like title, description, price, product images, stock quantity, and categories.

**Testing and Debugging:** Conducted various tests to ensure the functionality of all features, fixing bugs, and ensuring a smooth user experience.

# Day 6: Staging Deployment and Finalization

**Key Activities:

Staging Deployment:**
Deployed the frontend on Vercel, ensuring it is accessible via a staging URL for review.
Integrated the frontend with Sanity to fetch and display dynamic product listings, user data, and categories.

**User Testing:**
Ran end-to-end tests to ensure that users could browse products, add items to the cart, and complete a purchase seamlessly.
Fixed minor UI and UX issues based on feedback from team members.

**Final Adjustments**:
Finalized the eCommerce website’s design and usability for a smooth launch.
Ensured responsiveness and compatibility across different screen sizes.

# Key Challenges:

**Data Management with Sanity:** While Sanity’s headless CMS made content management flexible, ensuring that product data was properly structured and could be easily queried in the frontend was a learning curve.
Payment Gateway Integration: Ensuring smooth transaction processing and managing errors effectively.
Responsive Design: Ensuring the website was fully responsive and optimized for both mobile and desktop users.

**Final Outcome:**
By the end of the hackathon, the team successfully developed a functional eCommerce website with key features, including product listings, a shopping cart, and a payment gateway. The website was deployed to staging environments on Vercel for frontend and Sanity for backend content management. The project demonstrated a strong understanding of both frontend and backend development, as well as deployment pipelines.


**Skills & Technologies Gained:**
Proficiency in React.js and building dynamic UIs.
Experience with Sanity.io for structured content management and its integration into the frontend.
Familiarity with deployment tools like Vercel for frontend and Sanity Studio for backend content management.
Strong experience in responsive design and UX/UI principles.
