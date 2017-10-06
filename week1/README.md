# CS97 Discussion, Week 1
## Python
### If-else practice: #0

Write a function that returns the absolute value of a number

### If-else practice: #1

You've been asked to write the customer interface for ticket pricing at a theme park! Children two years old and under can enter the park for free. Children 12 and under get a discounted price of $40. Seniors also get a discounted price; anyone 65 or over only has to pay $60. Everyone else has to pay $85.

Write a function that takes in the age of a guest and returns the correct price.

### If-else practice: #1 Revisited

The theme parks wants to offer a special promotion to adults, but only if they live in California and only if they don't already get a special price (i.e. adults between the ages of 12-65). If they do, they get 15% off the regular entrance price. Your function now takes in a second argument that represents the two letter state code( "AL", "FL", "CA", "NV", etc).

How would you modify the code you wrote for the previous problem to incorporate this new policy?

### If-else practice: #2

Write a function that takes in three numbers and returns the smallest of the three.

### Bonus problem

Write a function that tells you whether or not a point is inside a circle.

* What arguments would you need?
* The traditional mathematical solution needs the square root function, but you don't need it to solve this problem. Can you do it using what you know?
* Reminder: pow(base, exponent) gives you the power. So pow( num, 2) can square something.

## Picobot
Go [here](http://web.cs.ucla.edu/~todd/picobot.html) to play the Picobot!
### Picobot practice problem

How do we make Picobot travel in a zigzag pattern across the (empty) board?

* From any given location, PicoBot should take one step north, then one step east, then one step north ad infinitum until it reaches a wall and can't go any farther
* It should never take two consecutive steps in the same direction.

For example, below is a valid zigzag pattern

![alt text](https://github.com/pakkaliu/CS97-Fall18/blob/master/week1/PicoZigZag.png "Picobot Zig Zag Example")

