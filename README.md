# Two Bucket Problem

Given two buckets of different size, write a program to demonstrate how to measure an exact number of liters by strategically transferring water between the buckets.

Since this mathematical problem is fairly subject to interpretation / individual approach, the tests have been written specifically to expect one overarching solution.

To help, the tests provide you with which bucket to fill first.

Your program will take as input:
- the size of bucket one, passed as a Number
- the size of bucket two, passed as a Number
- the desired number of liters to reach, passed as a Number
- which bucket to fill first, passed as a String (either 'one' or 'two')

Your program should determine:
- the total number of "moves" it should take to reach the desired number of liters, including the first fill - expects a Number
- which bucket should end up with the desired number of liters (let's say this is bucket A) - expects a String (either 'one' or 'two')
- how many liters are left in the other bucket (bucket B) - expects a Number

Note: any time a change is made to either or both buckets counts as one (1) move. 

Example: 
Bucket one can hold up to 7 liters, and bucket two can hold up to 11 liters. Let's say bucket one, at a given step, is holding 7 liters, and bucket two is holding 8 liters (7,8). If you empty bucket one and make no change to bucket two, leaving you with 0 liters and 8 liters respectively (0,8), that counts as one "move". Instead, if you had poured from bucket one into bucket two until bucket two was full, leaving you with 4 liters in bucket one and 11 liters in bucket two (4,11), that would count as only one "move" as well.

So the only valid moves are:
- pouring from one bucket to another
- emptying one bucket and doing nothing to the other
- filling one bucket and doing nothing to the other

One last rule: when starting with the larger bucket (bucket two), you are NOT allowed at any point to have bucket one full and bucket two empty (the opposite starting point); that would defeat the purpose of seeing the difference between the two approaches! 

Written with <3 at [Fullstack Academy](http://www.fullstackacademy.com/) by [Lindsay](http://github.com/lindslev).

## Making the Test Suite Pass

Execute the tests with:

```bash
$ jasmine-node .
```

In many test suites all but the first test have been skipped.

Once you get a test passing, you can unskip the next one by
changing `xit` to `it`.

## Source

http://demonstrations.wolfram.com/WaterPouringProblem/