# Renovo Checkout Kata
This repository is primarily used as an interview kata for our job candidates.  It replicates our tech stack in a single Visual Studio solution, using ASP.NET WebAPI and Angular 2, running locally on IIS express.

# Installation and usage
(coming soon, as we wrap up the actual project architecture)

# Kata goals and instructions
We’re going to see how far we can get in implementing a supermarket checkout that calculates the total price of a number of items. In a normal supermarket, items are identified using Stock Keeping Units, or SKUs. In our store, we’ll use individual letters of the alphabet (A, B, C, and so on). Our goods are priced individually. In addition, some items are multipriced: buy n of them, and they’ll cost you y dollars. For example, item ‘A’ might cost $50 individually, but this week we have a special offer: buy three ‘A’s and they’ll cost you $130. The price and offer table:

    Item  Price   Offer
    --------------------------
    A     50       3 for 130
    B     30       2 for 45
    C     20
    D     15

Our checkout accepts items in any order, so that if we scan a B, an A, and another B, we’ll recognize the two B’s and price them at $45 (for a total price so far of $95).

credits: inspired by and adapted from 7digital https://github.com/7digital/kata-checkout
