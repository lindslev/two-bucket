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
- how many liters are leftover in the other bucket (bucket B) - expects a Number

Note: any time a change is made to either or both buckets counts as one (1) move. 

Example: 
Bucket one can hold up to 7 liters, and bucket two can hold up to 11 liters. Let's say bucket one, at a given step, is holding 7 liters, and bucket two is holding 8 liters (7,8). If you empty bucket one and make no change to bucket two, leaving you with 0 liters and 8 liters respectively (0,8), that counts as one "move". Instead, if you had poured from bucket one into bucket two until bucket two was full, leaving you with 4 liters in bucket one and 11 liters in bucket two (4,11), that would count as only one "move" as well.

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