# Amazon Clone Website

This project is a fully functional Amazon clone built using HTML, CSS, and JavaScript. It features product listings, a shopping cart, search functionality, and a checkout process.

<img width="452" alt="Image" src="https://github.com/user-attachments/assets/f5a36c8a-659e-4296-bd94-e9e2d42347e5" />

## Live Demo:

Experience the live version of the website here: https://afreen1663.github.io/amazon_clone1/ 

## Features
- **Product Listing**: Displays various products with images, descriptions, and prices.
- **Add to Cart**: Users can add and remove products from their cart.
- **Search Functionality**: Allows users to search for specific products.
- **Cart Management**: Users can view, update, and remove items from their cart.
- **Checkout Process**: Saves cart data and redirects users to a confirmation page.
- **Responsive Design**: Works on different screen sizes.

## Technologies Used
- **HTML5**: Structure and layout.
- **CSS3**: Styling and responsiveness.
- **JavaScript (ES6+)**: Handles user interactions and data management.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Afreen1663/amazon_clone1.git
   ```
2. Navigate to the project directory:
   ```sh
   cd amazon_clone
   ```
3. Open `index.html` in a browser to start using the Amazon clone.

## Usage
1. Browse products from the homepage.
2. Click on a product to view details.
3. Add items to the cart.
4. Click on the cart icon to view the cart.
5. Proceed to checkout.

## Sample Code (Adding Items to Cart)
```javascript
function addToCart(product) {
    const existingItem = cart.find(item => item.id === product.id);
    if (existingItem) {
        existingItem.quantity += 1;
    } else {
        cart.push({ ...product, quantity: 1 });
    }
    updateCartCount();
    alert(`${product.name} added to cart!`);
}
```

## Future Improvements
- Implement user authentication.
- Add payment gateway integration.
- Improve UI/UX with better animations and layouts.
<br />
* Make sure you have downloaded all the required files including the images.*
