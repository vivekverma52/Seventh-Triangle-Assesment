
Overview
The Page built with HTML, CSS, and JavaScript. It fetches products dynamically from an API, displays them in responsive cards, and provides sorting functionality.

Features
Product Fetching
Products are fetched from the API: https://interveiw-mock-api.vercel.app/api/getProducts
Responsive Layout
4 cards per row (Desktop), 2 per row (Tablets), and 1 per row (Mobile).
Dynamic Sorting
Sort products by Price: Low to High or High to Low using a dropdown menu.
Loader Animation
Displays a bouncing dots loader while fetching products.
Add to Cart Buttons
Each product card has an "Add to Cart" button with a shopping cart icon.
Installation
---------------------------------------------------------------------------------------
Clone the repository or copy the code.
Save index.html, style.css, and script.js in the same directory.
Link FontAwesome for icons: html
Copy code
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
---------------------------------------------------------------------------------------
Usage
Open index.html in a browser.
Click "Load Products" to fetch and display items.
Use the "Sort By" dropdown to sort prices dynamically.
---------------------------------------------------------------------------------------------
Technologies Used
HTML5
CSS3 (Responsive design, animations)
JavaScript (API integration, sorting logic)
API Details
Endpoint: https://interveiw-mock-api.vercel.app/api/getProducts
Response: JSON format with product details and price variants.
Responsive Breakpoints
Desktop: 4 cards/row
Tablet (≤ 768px): 2 cards/row
Mobile (≤ 480px): 1 card/row
------------------------------------------------------------------------------------
Run the project in a local browser to test dynamic fetching and sorting. 🚀
