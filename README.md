# Next.js Stripe Checkout

This is a simple app showing you how to setup Stripe Checkout on a Next.js project in order to accept payments.

The steps involved to get this to work are:

-   Clone the repository
-   Run: npm install
-   Log into your Stripe account (create one first if you don't have one)
-   Enable test mode
-   Click the gear icon in the top right
-   Then under the "Business settings" click on "Account details"
-   Fill in a "Public business name", "Support phone number", and "Statement descriptor"
-   Click on "Developers" and then "API keys"
-   Copy your publishable key and secret key, and place it in the .env file
-   Click on "Products" and create a product
-   Copy the price ID, go into src/pages/api/checkout_sessions.js and paste it where you see "{{PRICE_ID}}"
-   Copy the URL of your product image, go into src/pages/index.js and paste it where you see "{{IMAGE_URL}}"
-   Then you can run "npm run dev" in your terminal to run the development server
