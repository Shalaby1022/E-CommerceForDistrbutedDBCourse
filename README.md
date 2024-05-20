# MEAN Stack Online Food Store

This project is a sample implementation of an online food store using the MEAN stack (MongoDB, Express.js, Angular, Node.js). It includes various features such as [food listing](#food-list), [search functionality](#search-functionality), [tag filtering](#tags-bar), [cart management](#cart-page), [user authentication](#login-page), [MongoDB integration](#mongodb-integration), [order management](#order-management), and more.

## Features

### [Food List](#food-list)
- Generate component for listing foods.
- Create Food model and data.ts for sample foods.
- Add images to assets folder.
- Create Food service.
- Generate Home component with TS, HTML, and CSS.

### [Search Functionality](#search-functionality)
- Add search method to Food service.
- Add search route and display results in Home component.
- Generate and integrate search component with TS, HTML, and CSS.

### [Tags Bar](#tags-bar)
- Create Tag model and add sample tags to data.ts.
- Extend Food service with methods for tags.
- Add routes for tags and display tag results.
- Generate Tags component with TS, HTML, and CSS.

### [Food Page](#food-page)
- Add method to Food service for individual food details.
- Generate Food Page component with TS, HTML, and CSS.
- Add route for Food Page.

### [Cart Page](#cart-page)
- Create CartItem and Cart models.
- Generate Cart service.
- Add "Add to Cart" button on Food Page.
- Generate Cart page component with TS, HTML, and CSS.
- Add route for Cart Page.

### [Not Found Page](#not-found-page)
- Generate 404 component with TS, HTML, and CSS.
- Integrate into Home, Food, and Cart pages.

### [Backend Connection](#backend-connection)
- Set up backend folder, initialize npm and TypeScript.
- Copy data.ts to backend.
- Install and set up Express and other required packages.
- Create server and APIs, and configure frontend to use backend services.

### [Login Page](#login-page)
- Generate Login component and integrate with routes.
- Implement login functionality using Reactive Forms and APIs.
- Set up JSON Web Token (JWT) for authentication.
- Create User service and integrate login/logout functionality.

### [MongoDB Integration](#mongodb-integration)
- Move APIs to routers, set up MongoDB Atlas.
- Configure environment variables and install necessary packages.
- Connect backend APIs to MongoDB.
- Implement user registration and connect to MongoDB.

### [Checkout Page](#checkout-page)
- Create Order model and Checkout Page component.
- Integrate Cart and User services with Checkout.
- Generate Order Items List component.
- Add map functionality using Leaflet for address input.

### [Order Management](#order-management)
- Save orders with order model and status enum.
- Create Auth middleware and Order Router.
- Implement create API and Order service methods.

### [Payment Page](#payment-page)
- Generate Payment component and integrate with Order service.
- Implement Paypal payment system.
- Set up Paypal button and API.

### [Order Tracking](#order-tracking)
- Generate Order Track component and integrate with routes.
- Implement API for tracking orders.
- Add tracking methods to Order service.

## Setup Instructions

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies for both backend and frontend.
