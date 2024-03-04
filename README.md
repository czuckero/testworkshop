# testworkshop

Unit Tests:

1. A function called "multiplication" that returns the product of the two input numbers.

   - Expect the function to have two parameters
   - Expect the function to be given numbers as arguments
   - Expect the function to return the product of both the numbers
   - Expect (2, 3) to be a number
   - Expect (2, 5) to be equal to 10
   - Expect ("abc", 5) to be an error

2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

   - Expect the function to have two parameters
   - Expect the function to be given two arrays as arguments
   - Expect the function to concatenate the two arrays
   - Expect to filter out the odd numbers and sort them into a new array
   - Expect any duplicate numbers in the arrays given to be returned as one number
   - Expect ([1, 2, 3, 6], [5, 5, 8,]) to return ([1, 3, 5])
   - Expect the function to filter out any strings and return only numbers

Functional Tests:

1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

   - When user clicks checkout they are prompted with a window that gives them the option to create an account or checkout as a guest
   - The user creates an account
   - The user browses items on the website and adds three items to the cart
   - The items added appear in the cart
   - The user clicks checkout and it takes them to delivery options
   - The user inputs their delivery options
   - The feature takes them to the payment options
   - The user inputs their payment method
   - The feature shows them a summary of their order with the items in the cart, delivery info, and payment method displayed as well as the total
   - User has the option of going back to the main site to add more items

   - If there is nothing in the shopping cart, the user should be notified and the checkout button won't work
   - If the user inputs an invalid delivery information or payment method it will return an error and not allow the user to checkout.
