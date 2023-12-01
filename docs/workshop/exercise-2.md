---
layout: default
title: Exercise 2
parent: Workshop
permalink: /workshop/exercise-2/
nav_order: 2
---
## Exercise 2
### Identifying tests from the requirements

Let's look again at [Part 1](/workshop/day-1-part-1/) of the puzzle.

![Puzzle requirements](/../assets/requirements2.png)

The next part of the puzzle shows us what a puzzle input may look like and we can see for ourselves it represents 5 `Elves` because there are 5 separate blocks of numbers, each separated by a new line, which we already know represents creating a new `Elf`.

What's more, the puzzle is actually giving us some test cases.
* The first `Elf` should be carrying the sum of `1000 + 2000 + 3000 = 6000` calories
* The second `Elf` is carrying only a single item so should have a calorie count of `4000`
* The third `Elf` should be carrying the sum of `5000 + 6000 = 11000` calories
* The fourth `Elf` should be carrying the sum of `7000 + 8000 + 9000 = 24000` calories
* The fifth `Elf` is carrying only a single item so should have a calorie count of `10000`

Add additional tests to the `TestElfShould` class to capture the above scenarios.

Once you're happy your solution can solve the provided test cases, lets go to [Exercise 3](/workshop/exercise-3/). Remember if you get stuck you can always check out the [exercise-2](https://github.com/jpgough/advent-of-tdd/tree/exercise-2) branch for a solution.

