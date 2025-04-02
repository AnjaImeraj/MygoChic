# MygoChic
MyGo Chic Online Store Management System

Group Division (Phase I)

Team Information

Team Name: MyGo Chic 

Team Leader:
	•	Aleksandra Myslimi
	•	GitHub Username: aleksandramyslimi
 
Team Members:
	1.	Aleksandra Myslimi - GitHub:  aleksandramyslimi
	2.	Anja Imeraj - GitHub: AnjaImeraj
 
________________________________________
Project Details

Project Title: MyGo Chic Online Store Management System

Problem Statement:
Many small online clothing stores rely on Instagram for sales but lack a proper e-commerce platform to manage products, orders, and customers efficiently. This leads to challenges such as order tracking issues, difficulty in managing inventory, and lack of insights into customer behavior.

Solution Proposed:
We propose developing a web-based platform for mygo.chic that integrates with Instagram, allowing users to:

	•	Browse and filter products easily.
 
	•	Add items to a cart and complete purchases.
 
	•	Provide store admins with a dashboard to manage inventory, orders, and promotions.
 
	•	Offer analytics to improve marketing strategies.
 
Project Scope:

Aim:To build an efficient and user-friendly e-commerce system for mygo.chic, enhancing its online presence and order management.

Main Objectives:

	1.	Develop a responsive web application with an intuitive UI.
 
	2.	Implement a secure authentication system for users and admins.
 
	3.	Provide a shopping cart and checkout process with payment integration.

	4.	Enable admins to manage inventory and orders easily.
 
	5.	Ensure data security and encryption for user transactions.
 
Application Description:

The MyGo Chic Online Store Management System will be a web-based platform where customers can browse clothing items, filter products, add them to a cart, and place orders. The admin panel will allow store owners to update stock, manage orders, and analyze sales trends. The system will also support Instagram integration for product visibility.
________________________________________
Roles and Tasks Distribution

Team Leader Responsibilities:

	•	Manage the project timeline and tasks.
 
	•	Oversee the development process and ensure quality.
 
	•	Maintain the GitHub repository and documentation.
 
Main Roles and Tasks:

	1.	Aleksandra Myslimi - Backend Development (Database, Authentication, API)
 
	2.	Anja Imeraj - Frontend Development (UI/UX, Responsive Design, User Experience)
 
Both members will collaborate on testing, debugging, and final deployment.
________________________________________
Deadline

Submission Deadline: 15.03.2025, 23:59 hours.

GitHub Repository

Repository Name: SE_Project_Phase1_Mygo_Chic

GitHub Link: https://github.com/AnjaImeraj/MygoChic

Additional Notes

	•	The README.md file will include setup instructions, dependencies, and how to run the project.
 
	•	Future phases will involve refining user requirements, system architecture, and full implementation.

 

 Phase II: User Requirements and Application Specifications

1. Chosen Development Model

Model: Agile

-Why?

Agile is flexible and allows frequent updates. Since mygo.chic is an online clothing store, it needs regular updates for new collections, promotions, and customer feedback. Agile helps in making quick changes.


2. User Requirements

a. Stakeholders

	•	Customers: Browse and buy clothes.
 
	•	Store Admin: Manages products, orders, and promotions.
 
	•	Developers: Build and maintain the system.

	•	Marketing Team: Runs ads and tracks sales.

b. User Stories

	1.	As a customer, I want to browse clothes by category so I can easily find what I like.
 
	2.	As a customer, I want a simple checkout process so I can buy products without issues.
 
	3.	As an admin, I want to track inventory so I can restock items on time.

3. Functional Requirements

a. What the System Should Do:

	•	Users can browse products and filter them.
 
	•	Customers can add items to a cart and check out.
 
	•	Admins can add, edit, and remove products.

b. Acceptance Criteria (How We Know It Works)

	•	The product search returns results in under 2 seconds.
 
	•	Checkout supports at least two payment options.
 
	•	Admins can update stock in real time.

4. Non-Functional Requirements

a. System Performance & Quality:

	•	Speed: Pages should load in under 3 seconds.
 
	•	Security: User data (passwords, payments) should be encrypted.
 
	•	Usability: The site must work well on mobile devices.

b. Acceptance Criteria:

	•	The homepage loads within 3 seconds.
 
	•	Passwords are securely stored.
 
	•	The site is fully mobile-friendly.

5. Application Specifications

a. System Architecture

	•	Frontend: React.js (for an interactive website)
 
	•	Backend: Node.js with Express.js (handles logic)
 
	•	Database: MongoDB (stores users, products, and orders)

b. Database Model (Main Tables)

	•	Users (UserID, Name, Email, Password)
 
	•	Products (ProductID, Name, Price, Stock)
 
	•	Orders (OrderID, UserID, Products, TotalPrice)

c. Technologies Used

	•	React.js (for the website)
 
	•	Node.js + Express.js (backend)
 
	•	MongoDB (database)
 
	•	Stripe API (for payments)

d. User Interface (UI) Design

	•	Homepage with product categories
 
	•	Product pages with filters and search
 
	•	Shopping cart and checkout pages

e. Security Measures

	•	Encryption: SSL for secure browsing, bcrypt for passwords
 
	•	Authentication: Users log in with JWT tokens
 
	•	Admin Controls: Only admins can edit products


