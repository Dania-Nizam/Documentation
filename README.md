# Rental E-Commerce Marketplace  

##  Day 1 - Hackathon Progress  

On **Day 1 of the Hackathon**, I selected my **marketplace type** as a **rental e-commerce platform**. I clearly defined my **business goals**, outlining the key objectives and vision for the platform.  

I identified the **problems my marketplace aims to solve**, ensuring that it addresses specific user pain points effectively. Additionally, I defined my **target audience**, focusing on the demographics and user segments that would benefit the most from my platform.  

I then outlined my **products and services**, detailing the offerings that set my marketplace apart. To highlight its **uniqueness**, I identified key differentiators that make my platform stand out in the competitive market.  

To establish a strong technical foundation, I created a **data schema**, structuring the relationships between entities. Finally, I **visualized the schema**, ensuring clarity in data organization and scalability.  


# Rental E-Commerce Marketplace - Day 2: Technical Planning  

## ✅ Task Completed: Technical Foundation  

### 1. **Define Technical Requirements**  
I translated my business goals into clear technical requirements for the marketplace. For each feature identified on Day 1, I outlined the following:  
- **Frontend Requirements:**  
  - User-friendly interface for browsing products.  
  - Responsive design for both mobile and desktop users.  
  - Essential pages: Home, Product Listing, Product Details, Cart, Checkout, and Order Confirmation.  

- **Sanity CMS as Backend:**  
  - Utilized Sanity CMS to manage product data, customer details, and order records.  
  - Focused on designing schemas in Sanity to align with the business goals defined on Day 1.  

 

### 2. **Design System Architecture**  
I created a high-level diagram illustrating how system components interact:  
- **Frontend (Next.js)** interacts with **Sanity CMS** for product data management.  


I visualized the data flow, demonstrating how users interact with the frontend, order details are recorded in Sanity CMS.


### 4. **Write Technical Documentation**  
I documented the system architecture, workflows, and API requirements in a structured format.  
- Described the interaction between components and data flows.  
- Provided clear API specifications and examples.  
- Created a technical roadmap for the project's implementation.  

### 5. **Collaborate and Refine**  
I engaged in discussions with peers and mentors, sharing ideas and receiving constructive feedback to improve the system architecture, API design, and overall project plan.  

By the end of Day 2, I achieved the following:  
- A comprehensive technical plan aligned with business goals.  
- Visualized system architecture with tailored workflows.  
- Detailed API requirements and schema designs.  
- Collaborative feedback incorporated into the plan.  




# Rental E-Commerce Marketplace - Day 3: API Integration and Data Migration  

## ✅ Task Completed: API Integration and Data Migration  

### 1. **Understand the Provided API**  
I thoroughly reviewed the API documentation for the assigned template and identified key endpoints, such as:  
- **Product Listings:** `/products`  
- **Categories:** `/categories`  


### 2. **Validate and Adjust My Schema**  
I compared my existing **Sanity CMS schema** (created on Day 2) with the API data structure. Adjustments were made to field names, types, and relationships to ensure compatibility.  
- Example:  
  - **API Field:** `product_title`  
  - **Sanity Schema Field:** `name`  
  I adjusted my schema accordingly to ensure proper mapping during data migration.

### 3. **Data Migration Options**  
I explored multiple methods for data migration and ensured validation of all data:  
- **Using the Provided API:**  
  I wrote scripts to fetch and transform data from the API.  
- **Manual Import:**  
  I exported data as JSON or CSV and used Sanity's built-in import tools for uploading.  
- **Using External Platform APIs:**  
  I fetched data from external platforms  and mapped fields to my Sanity schema.  



### 4. **API Integration in Next.js**  
I successfully integrated the APIs into my frontend project, ensuring robust error handling and modular coding for scalability.  
- **Steps Completed:**  
  - Created utility functions for fetching data from the API.  
  - Rendered API data in components on the frontend.  
  - Tested API integration using Postman and browser developer tools.  

**Error Handling Tips Applied:**  
- Logged errors for debugging.  
- Displayed user-friendly error messages.  
- Used **skeleton loaders** to enhance user experience.

### 5. **Expected Output**  
- **Sanity CMS** populated with data from:  
  - The provided API.  
  - External sources.  
  - Manually uploaded data.  

- **API integration in Next.js** displayed:  
  - Product listings.  
  - Categories.  
  - Other relevant data.

### 6. **Submission Requirements**  
I documented the API integration process, adjustments to schemas, migration steps, and tools used.  
- **Screenshots:**  
  - API calls and responses.  
  - Data displayed on the frontend.  
  - Populated Sanity CMS fields.  

- **Code snippets** for API integration and migration scripts are included in the report.  

### 7. **Best Practices Followed:**  
- Stored sensitive data like **API keys** securely using `.env` files.  
- Followed **clean coding practices** (modularized functions, descriptive variable names, and comments).  
- Validated all data during migration and logged discrepancies for further investigation.  
- Used **version control** with frequent commits and meaningful messages.  
- Thoroughly tested API integration, handling edge cases like empty responses or invalid data.  
- Engaged in **peer reviews** for feedback and improvement.

### 8. **Portfolio-Ready Submission**  
I’ve compiled a polished report documenting the API integration and data migration steps, ready for submission.  



# Rental E-Commerce Marketplace - Day 4: Building Dynamic Frontend Components  

## ✅ Task Completed: Dynamic Frontend Components  

### 1. **Objective**  
On Day 4, the focus was on designing and developing dynamic frontend components to display marketplace data fetched from **Sanity CMS** or APIs. The emphasis was on creating modular, reusable components, applying state management techniques, and ensuring responsive design and UX/UI best practices.

### 2. **Key Components Built:**  
- **Product Listing Component:**  
  - Rendered product data dynamically in a **grid layout**.  
  - Displayed product details such as name, price, image, and stock status in card format.

- **Product Detail Component:**  
  - Implemented **dynamic routing** in Next.js for individual product detail pages.  
  - Included product description, price, and available sizes/colors.

- **Category Component:**  
  - Displayed categories dynamically, fetched from Sanity CMS or the API.  
  - Enabled **filtering** of products by selected categories.

- **Search Bar Component:**  
  - Implemented search functionality to filter products by name or tags.

- **Cart Component:**  
  - Created a cart component displaying added items, quantity, and total price.  
  - Applied **state management** using React's `useState` to track cart items.

- **Wishlist Component:**  
  - Enabled users to save products for future reference.  
  - Persisted data using **local storage** for the wishlist.

- **Checkout Flow Component:**  
  - Built a **multi-step form** for the checkout process with fields for billing, shipping address, and payment details .

- **Login logout:**  
  - I add the login and logout function.

- **Reviews and Ratings Component:**  
  - Allowed users to view and submit product reviews.  
  - Displayed average ratings and individual reviews dynamically.



- **Filter Panel Component:**  
  - Created an advanced filter panel with options like price range sliders, type selection, and availability toggles.

- **Footer and Header Components:**  
  - Built consistent navigation and branding elements.  
  - Ensured responsiveness and accessibility across devices.

### 3. **Frontend Best Practices Applied:**  
- **Reusable Components:**  
  - Built modular components like `ProductCard` and `CategoryFilter` for reuse across pages.  
  - Passed data via props to maintain flexibility.

- **State Management:**  
  - Used React state (`useState`) for local component states and **context** for global state management when necessary.

- **Styling:**  
  - Styled components using **Tailwind CSS** for a responsive design across mobile and desktop views.



### 4. **Steps for Implementation:**  
- **Setup:**  
  - Ensured the **Next.js** project is connected to **Sanity CMS** or the chosen API.  
  - Tested data fetching to confirm availability of product and category data.

- **Component Building:**  
  - Built and tested components, ensuring they are dynamic and data-driven.




# Rental E-Commerce Marketplace - Day 5: Testing, Error Handling, and Backend Integration Refinement

## ✅ Task Completed: Testing, Error Handling, and Backend Integration Refinement

### 1. **Objective**  
On Day 5, the focus was on preparing the marketplace for real-world deployment by ensuring all components are thoroughly tested, optimized for performance, and ready to handle customer-facing traffic. Key activities included:  
- Performing comprehensive testing: functional, non-functional, user acceptance, and security.  
- Implementing robust error handling mechanisms.  
- Optimizing the marketplace for speed and responsiveness.  
- Ensuring cross-browser compatibility and device responsiveness.  
- Preparing documentation for testing results.

### 2. **Key Areas of Focus:**  

- **Functional Testing:**
  - Validated core features such as product listing, cart operations, and user profile management.
  - Ensured proper display of product details, dynamic routing, and filters/search functionality.
  - Tested using tools like **Postman** for various scenarios.

- **Error Handling:**
  - Implemented error messages for network failures, invalid data, and unexpected server errors.  
  - Added fallback UI elements such as "No products available" when the API returns no data.

- **Performance Testing:**
   
  - Analyzed performance using **page speed insight** and made improvements such as reducing unused CSS and enabling browser caching.  
  - Targeted an initial page load time under 2 seconds.

- **Cross-Browser and Device Testing:**
  - Tested the marketplace on popular browsers: Chrome, Firefox, Safari, and Edge.  
  - Ensured consistent rendering and functionality across browsers.  
  - Used **BrowserStack** for responsive testing and manual testing on physical devices.





### 3. **Steps for Implementation:**  
- **Step 1: Functional Testing**  
  - Validated core features like product listing, filters, cart operations, and dynamic routing.  
  - Tested APIs using **Postman** and UI components using **Cypress**.

- **Step 2: Error Handling**  
  - Added **try-catch** blocks for handling API errors and displaying user-friendly messages.  
  - Displayed fallback UI when data was unavailable.

- **Step 3: Performance Optimization**  
  - Compressed and optimized assets for faster load times.  
 
  - Improved performance metrics using  **Google PageSpeed**.

- **Step 4: Cross-Browser and Device Testing**  
  - Verified compatibility across multiple browsers.  
  - Used **BrowserStack** and physical devices for testing.



- **Step 5: Documentation Updates**  
  - Documented key testing results, issues found, and fixes applied.  
  - Prepared a detailed **CSV-based test report** and ensured proper formatting.




# Rental E-Commerce Marketplace - Day 6: Deployment Preparation and Staging Environment Setup

## ✅ Task Completed: Deployment Preparation and Staging Environment Setup

### 1. **Objective**  
Day 6 focused on preparing the marketplace for deployment by setting up a staging environment, configuring hosting platforms, and ensuring readiness for customer-facing use. This stage included:  
- Setting up a staging environment for testing the application in a production-like setting.  
- Configuring environment variables securely for deployment.  
- Conducting staging environment testing (functional, performance, security).  
- Organizing project files in a structured GitHub repository.

### 2. **Key Areas of Focus:**  

- **Deployment Strategy Planning:**
  - Chose **Vercel** as the hosting platform for easy deployment and seamless integration with the GitHub repository.
  - Connected the GitHub repository to Vercel for automatic builds and deployments.

- **Environment Variable Configuration:**
  - Created a `.env` file with sensitive data such as API keys and project IDs.  
  - Uploaded environment variables securely through the Vercel dashboard to ensure secure deployment.

- **Staging Environment Setup:**
  - Deployed the marketplace to the staging environment for validation.  
  - Ensured deployment builds successfully and the site loads correctly.

- **Staging Environment Testing:**
  - Conducted **functional testing** using **Cypress** to validate product listing, search, and cart operations.
  - Ran **performance testing** using **Lighthouse** and **GTmetrix** to analyze load times, speed, and responsiveness.
  - Conducted **security testing** to validate input fields, ensure **HTTPS** communication, and secure API handling.
  - Verified responsiveness and error handling across devices.

- **Documentation Updates:**
  - Updated **README.md** to summarize all activities from Day 1 to Day 6.  
  - Documented all testing results in a structured GitHub repository, including test cases and deployment instructions.

### 3. **Steps for Implementation:**  
- **Step 1: Hosting Platform Setup**  
  - Chose **Vercel** for easy deployment and integration with the GitHub repository.  
  - Connected the GitHub repository to **Vercel** and configured the build settings for automatic deployment.

- **Step 2: Configure Environment Variables**  
  - Created a `.env` file to include sensitive data like API keys. Example:  
    ```env
    NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
    NEXT_PUBLIC_SANITY_DATASET=production
    API_KEY=your_api_key
    ```

  - Uploaded environment variables securely through the **Vercel** dashboard.

- **Step 3: Deploy to Staging**  
  - Deployed the application to **Vercel** for staging.  
  - Verified that the build process completed successfully and the site functioned correctly in the staging environment.

- **Step 4: Staging Environment Testing**  
  - **Functional Testing:** Verified features like product listing, search, and cart operations.  
  - **Performance Testing:** Analyzed speed and responsiveness **.  
  
  - **Test Case Reporting:** Documented test cases and results in a CSV file.





