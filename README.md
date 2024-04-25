# Round-Up-Amount-Changer
This script runs on a BigCommerce checkout page and determines the amount of a donation round-up. It is meant for non-profits to use, as most existing solutions are for for-profits intending a pass-through donation.

To use, add to your Script Manager and make sure it runs on Checkout pages in the settings. Also add an item for $0.01 with the SKU ROUND-1. This item will cause the user's cart to round up to the nearest $1 when it is in the cart and taxes/shipping have been calculated at checkout. This project also supports $5 and $10 round-ups with the SKUs ROUND-5 and ROUND-10 , respectively.
