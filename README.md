# Sarang — Objects with soul

A responsive, front-end ecommerce storefront for a curated home, wear, and objects collection.

## Run it

Open `index.html` in a browser. No build tools or dependencies are required. Product photography and web fonts load from external services, so an internet connection improves the experience.

## Project structure

- `index.html` — home page and GitHub Pages entry point
- `pages/` — shop, product, cart, login, seller, and about pages
- `assets/css/` — shared storefront styles and page layouts
- `assets/js/` — shared catalog, cart, account, seller, and recommendation logic
- `README.md` — project notes and setup

## Pages

- `index.html` — home and featured collection
- `pages/shop.html` — searchable, filterable product catalog
- `pages/product.html?id=1` — product detail (the ID selects the product)
- `pages/cart.html` — persistent shopping bag and order summary
- `pages/about.html` — brand story and values
- `pages/login.html` — customer or seller demo account registration and sign-in
- `pages/seller.html` — seller-only product listing studio

## Included

- Product browsing by category, with search and price sorting
- Related-item recommendations when a search has no exact match
- Personalized product picks ranked from recent product views, category browsing, searches, favourites, and cart activity
- Favourite toggles and a shopping bag with quantity controls
- Seller listings saved in this browser and added to the shop catalog
- Persistent cart saved in the browser's local storage
- Free-shipping progress, newsletter demo, responsive navigation, and checkout demo

Checkout and newsletter subscription are interface demos; no payments or email data are sent. Login, seller listings, and on-device recommendation ranking are local browser prototypes, not production authentication, a trained AI service, or a shared marketplace backend. Accounts, listings, and recommendation history do not sync across devices.
