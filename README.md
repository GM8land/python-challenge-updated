## Module 2 Challenge: Interactive ordering system for Food Truck menu
### Challenge Instructions
The starter code provided includes the code for printing the menu for the customer, which was part of one of your Day 3 activities. You will be adapting this menu to allow customers to place an order, which includes storing the customer's order and printing the receipt with the total price of all items ordered. The starter code includes comments, which you may use as a guide for the steps you need to add

### Requirements
- Order System (54 points)
  - An order list is initialized. (2 points)
  - User is prompted for their menu item selection and it's saved as a variable menu_selection. (4 points)
  - User input menu_selection is checked as a number and an error is printed if it is not. (4 points)
  - menu_selection is converted to an integer. (2 points)
  - An if-else statement is used to check if menu_selection is in the menu_items keys, and an error is printed if it isn't. (4 points)
  - The item name of the customer's selection is extracted from the menu_items dictionary and stored as a variable. (4 points)
  - The customer is prompted for a quantity of their item selection and the value defaults to 1 if the customer does not input a valid number.     (10 points)
  - The customer's selected item, price, and quantity are appended to the order list in dictionary format. (10 points)
  - A match-case statement is used to check if the customer would like to keep ordering, and performs the correct actions for y, n, and             default cases. (10 points)
  - The match-case statement converts the use input to lowercase or uppercase before checking the case. (4 points)
- Order Receipt (46 points)
  - A for loop is used to loop through the order list. (10 points)
  - The value of each key in each order dictionary is saved as a variable. (6 points)
  - The number of formatting spaces are correctly calculated. (6 points)
  - Space strings are created using string multiplication. (4 points)
  - The customer's order is printed with the item name, price, and quantity. (6 points)
  - List comprehension is used to calculate the total price of the order. (10 points)
  - The total price of the order is printed to the screen. (4 points)
### Grade: 88



### Grader Feedback Received:
Hi Geoff,
Great work on your Module 2 python-challenge-1 submission! Your code demonstrates a solid understanding of the key concepts and requirements. 
I'm impressed with how you initialized the order list and prompted the user for their menu selection. Your input validation for the menu selection was spot on, checking if it's a number and converting it to an integer. Well done using an if-else statement to verify the selection is valid based on the menu_items keys.
Your code handles prompting the customer for the quantity of their selected item effectively, defaulting to 1 if invalid input is provided. Nicely done appending the customer's item details to the order list in dictionary format.
I like how you implemented a loop to continue taking orders until the customer chooses to finish ordering. The logic works well, though using a match-case statement as specified in the instructions would make it even cleaner and allow handling of uppercase, lowercase, and default inputs more consistently.
Your receipt printing logic is quite strong. The for loop to iterate through the order list is perfect. I appreciate how you store the item details as variables and calculate the formatting spaces correctly. The receipt output looks great!
One small area for improvement is in calculating the order total. While your approach of calculating the item costs in the loop and summing them afterward works, using list comprehension as described in the requirements would streamline it further.
Overall, this is an excellent submission demonstrating your strong grasp of the module's objectives. Keep up the fantastic work!

Best regards,
C.G - Learning Specialist
Central Grader , May 22, 2024 at 1:15pm
