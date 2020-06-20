#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime complexity of this algorithm is log(n) because it is initially cubes n and will run when a is less than n cubed. The incrementor runs as many times as n. Since the squaring n reduces cubing of n to just the amount of n. The while loop will only run as many times as n.


b) The runtime complexity of this is log(n^2). It's quadtratic time because it performs a linear time operation for as many inputs as there is. j*2 is linear as it only multiples 1 and doubles it. It will do that for how every many n is.


c) In this code snippet, bunnies will never reach 0 since it is technically adding 1 everytime. If bunnies was a negative number, than it would be O(n). But this would be an infinite loop if it was anything above 0.

## Exercise II

To determine which floor the egg would not break on, I would start out by testing the exact middle floor. So I would take n and divide it by two. Test that floor out. If the egg breaks, you know it's going to be below, so you can cut the top half of the building out, and if it doesn't break, you can cut the bottom half out. Then I would cut n in half a second time and test the middle. If it breaks, use the lower half of that half, if it doesn't you can use the upper half. I believe this would reduce the amount of eggs broken and would run at a O(log n) time complexity, since you are not testing each floor, and would be reducing your testing by at least half.
