# python-challenge-1

## This code runs a interactive ordering system from a food truck menu.

### Ordering System
The data structure used to store the details of the menu is a dictionary.

1. Uses an empty list to store the ongoing order to process the price later.
2. User is prompted to choose items from a cascading list of items that start as the main food category followed by the unique items. Some items have customizations available which is also shown as a prompt.
3. There is a block of code placed after accepting input for error handling.
4. The selected item details are saved into variables to append into the order list.
5. A match case tries the user to see if they want to continue ordering more items or proceed to checkout. The match case converts inputs to lower case to simplify cases.

### Order Receipt

1. A loop traverses through the order list.
2. Each of the values per key is saved as variable to calculate spaces during print formating.
3. The spaces are calculated using string multiplication subtracting the length of the item string.
4. The order is finally printed in the desired format.
5. A final list comprehension runs to find the sum of the order to tell the user to the toal price of the order. 
    >_There also exists a comment segment of code that reduces the time complexity by doing the calculation during the printing loop itself._
6. The total price is shown to the user.