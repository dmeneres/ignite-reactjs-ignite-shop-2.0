# 04 - Ignite Shop
<p>This is a demonstration of a online store called Ignite Shop. Here are presented some Rocketseat shirts that are for sale. Integration with Stripe was made for payments purposes</p>

## Home page
![01](https://user-images.githubusercontent.com/90613379/207113118-2a46d70b-2ba5-4c4d-ab0a-e892fe4002a2.png)
Here you'll see all products shown with a carousel.

## Product page
![02](https://user-images.githubusercontent.com/90613379/207113174-110d67b5-01c5-4c12-b230-48f08829b6bd.png)
Specific product page with a brief description.

## Stripe checkout
![03](https://user-images.githubusercontent.com/90613379/207113296-c02145ab-656b-4a3f-a2a9-53aa275128a1.png)
Checkout session by stripe. 

## Success page
![04](https://user-images.githubusercontent.com/90613379/207113311-e271a6b4-66cd-436e-b122-12b5fb1e5952.png)
Final page that is rendered if you have a session id, otherwise it will redirect you to the home page. This session id is used to retrieve customer name and product purchased.

## Focus of this module
<ul>
  <li>NextJs (file system routing, spa vs ssr vs ssg, _document, ...)</li>
  <li>Stitches (css-in-js like styled-components but more adapted to nextjs)</li>
  <li>Stripe (payment platform)</li>
</ul>

------------------------====--------------------------

To run this project you'll need to create a stripe account (and create the products that can be found on <a href="https://www.figma.com/file/OIJJEW24DFiJO6XLqHw2DM/Ignite-Shop/duplicate">Figma</a>). Create a .env.local file with your public and secret API keys named (STRIPE_PUBLIC_KEY and STRIPE_SECRET_KEY) and a variable with your url (suggestion NEXT_URL=http://localhost:3000). Don't forget "npm i" and then "npm run dev" and you should be ready to go.
