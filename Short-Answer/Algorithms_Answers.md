#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This would end up being a complexity of O(n). Reason for this is it would run relative to whatever the value of n is.

b) Time complexity would end up being O(nlog(n)). It would definitely take a while for it to go through its full stack, but it's not going to take such a long time that it bogs down the system.


c) O(n) because its all dependent on what (bunnies) is.

## Exercise II
The simplest and most inefficient way you could go about solving this is just dropping an egg on each floor and find out if the egg breaks and continue going up til you find your base floor. Because at that point you know that from that point on the egg will continue to break. Another solution is to do n//2 to quickly search to see if the egg breaks. If it does, you continue this process til you find the floor where it does not break. This would be O(log(n)) time complexity.