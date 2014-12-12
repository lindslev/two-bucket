# Two Bucket Problem

Given two numbers x and y representing two buckets of x liters and y liters, write a program to demonstrate how to measure exactly z liters of water in only one of the two buckets.

Since this mathematical problem is fairly subject to interpretation / individual approach, the tests have been written specifically to expect one overarching solution.

To help, the tests provide you with which bucket to fill first.

The tests ask for the number of moves it should take to achieve the desired liters of water (the goal variable). Any time a change is made to either or both buckets (at the same time) counts as one (1) move.

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