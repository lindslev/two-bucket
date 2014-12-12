# Two Bucket Problem

Given two numbers x and y representing two buckets of x liters and y liters, write a program to demonstrate how to measure exactly z liters of water using only those two buckets (and a fictional body of water).

Since this mathematical problem is fairly subject to interpretation / individual approach, the tests have been written specifically to expect one overarching solution.

To help, the tests provide you with which bucket to fill first.

The tests ask for the number of moves it should take to achieve the desired liters of water. Any time a change is made to either or both buckets counts as one (1) move.

So for an input of 3, 5, 1, and 'one', we have:

	- one 3 liter bucket
	- one 5 liter bucket

.. and we want to figure out how to get exactly 1 liter using only those two buckets. The fourth input ('one') indicates which bucket you should fill first. To get exactly 1 liter will require a series of strategic moves between buckets.

Since the computer can't ask for the exact walkthrough of moves, it will expect:
	
	- the total number of moves it should take, including the first fill
	- which bucket should end with the desired number of liters (let's say this is bucket A)
	- how many liters are leftover in the other bucket (bucket B)


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