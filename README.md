# Grocery-Store

## Demo Video
[Grocery Demo](https://youtu.be/UcNkGD7viBg)


## System Features

### 1. User Features
- **Login and Authentication:**
  - Users can log in via `login.jsp`, which verifies credentials using `validateLogin.jsp`.
  - Sessions are managed for authenticated users, with a logout feature (`logout.jsp`) to ensure security.
- **Product Browsing and Search:**
  - `listprod.jsp` dynamically displays available products, fetching details from the database.
- **Product Reviews:**
  - `product.jsp` allows the logged-in user to review and read reviews on the product page.
- **Cart Management:**
  - Users can add items to their cart (`addcart.jsp`), view the cart's contents (`showcart.jsp`), and proceed to checkout.
  - The cart system integrates seamlessly with user accounts to track items.
- **Order Management:**
  - Orders can be reviewed and placed through `order.jsp` and `checkout.jsp`.
  - `listorder.jsp` allows users to view past orders.
- **Customer Details:**
  - Displays the logged-in customer’s information.

### 2. Administrative Features
- **Product Management:**
  - `admin.jsp` includes tools for:
    - Adding new products.
    - Updating or deleting existing products from the catalog.
- **Order Tracking:**
  - Admins can monitor orders using `listorder.jsp`.
- **Data Management:**
  - Administrative pages like `jdbc.jsp` and `loaddata.jsp` facilitate database interactions and maintenance tasks.

### 3. Additional Features
- **Dynamic Image Loading:**
  - Images are displayed using `displayImage.jsp`, enhancing user engagement.
- **Docker Integration:**
  - Docker configuration files (`Dockerfile` and `docker-compose.yml`) are included, allowing deployment in a containerized environment. This ensures consistency across different systems.
- **Reusable Components:**
  - Shared resources like `header.jsp`, CSS, and images improve code reusability and maintain a consistent interface.
- **Validation and Error Handling:**
  - Input validation (e.g., `auth.jsp`) ensures data integrity and prevents invalid entries.
  - Robust error handling mechanisms maintain system reliability.

## System Strengths
1. **Modular Design:**
   - Independent modules for user and admin functions improve maintainability.
2. **Scalability:**
   - Dockerized deployment supports scalability in production environments.
3. **User-Friendly Interface:**
   - Intuitive navigation and clear features enhance user experience.
4. **Security:**
   - Session management and input validation reduce vulnerabilities.

