Flip Deal Product Listing Page

Introduction

FlipDeal is an eCommerce company that has expanded its product range from fitness to now selling various kinds of phones.

Array of products: https://gist.github.com/imrhlrvndrn/21b7e1996abf7226c8beceb86a76c7b8

Instructions

Make sure you return the JSON of products in the format res.json({ products: sortedProducts }) where sortedProducts is the variable name used to store the result

Before declaring the API Endpoints, make sure you import cors to the code.

Note: Don’t forget to add:

let cors = require('cors');

app.use(cors());

Now, for FlipDeal you need to create APIs which filters out the products based on various conditions:

Once done, test your implemented code on the frontend here: https://bd2-listing-page.vercel.app/ after deploying it on Vercel.

What are the various user actions?

Select the following sorting options and see the products getting sorted:

Popularity
Price hight-to-low
Price low-to-high
Select any filter based on the:
RAM
ROM
OS
Brand
Price

The products are listed based on the filters applied.
