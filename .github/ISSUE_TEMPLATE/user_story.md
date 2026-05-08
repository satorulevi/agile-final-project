---
name: User Story
about: Create a user story for the agile final project
title: ''
labels: ''
assignees: ''

---

## User Story

As a **customer**  
I need **to view the items in my shopping cart**  
So that **I can confirm my selected products before checkout**
   
## Details and Assumptions

* The customer must be able to access the shopping cart from the website or app.
* The cart should show product names, quantities, prices, and the total amount.
* The customer should be able to review the cart before placing an order.
   
 ### Acceptance Criteria  
   
 ```gherkin
Given I am a logged-in customer with items in my shopping cart
When I open the shopping cart page
Then I should see all selected items with their quantities, prices, and total cost
 ```
