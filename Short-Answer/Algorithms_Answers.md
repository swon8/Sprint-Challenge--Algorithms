Add your answers to the Algorithms exercises here.

1a. O(n)
1b. O(n^3)
1c. O(n)

2. Divide the number of floors by 2 then move to that floor and drop an egg. If the egg breaks then the floor you want is below you so repeat the process on the floors below you. If the egg doesn't break the floor you want is above you (or you're on the correct floor) repeat the process on the floors above you. Eventually you'll have no more floors to repeat the process on and you'll get the right floor. O(log n)