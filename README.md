# Shopify-Liquid-Code version 2

# Shopify Liquid Coding Assignment

This repository contains the solution for the Shopify Liquid coding assignment with the following features:

## Tasks Implemented

### Task 1: Dynamic Product Badge
- Added conditional badges to product cards
- Shows "Budget Pick" for products under ₹500
- Shows "Limited Stock" for products with less than 5 in stock
- Both badges appear if both conditions are met

### Task 2: Custom Collection Filter
- Implemented a dropdown filter for product tags
- Filters work with "best-seller", "new-arrival", and "discounted" tags
- Maintains pagination while filtering

### Task 3: Personalized Greeting
- Displays time-appropriate greeting on the homepage
- Changes between morning, afternoon, and evening based on current time

### Task 4: Custom Upsell Section
- Shows different upsell products based on cart total
- Recommends accessories for carts under ₹1000
- Recommends premium items for carts ₹1000 and above
- Bonus: Added dynamic shipping message that updates based on cart total

## How to Install
1. Create a Shopify development store
2. Install the Dawn theme
3. Replace the respective liquid files with these versions
4. Create collections named "Accessories" and "Premium"
5. Add some test products with the custom tags mentioned in Task 2

## Testing
- Test each feature by:
  - Adding products with different prices and inventory levels
  - Applying tags to products
  - Viewing the homepage at different times of day
  - Adding items to cart to see upsell recommendations change
