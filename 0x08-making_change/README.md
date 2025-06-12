# Project: 0x08-making_change

## Objective

Solve the **coin change problem**: Given a list of coin denominations and a total amount, determine the minimum number of coins needed to make up that amount. If it's not possible to make the amount with the given coins, return -1.

## Problem Description

* Input:

  * An integer `amount` representing the total amount of money.
  * A list of integers `coins` representing the denominations of the available coins.
* Output:

  * An integer representing the minimum number of coins needed to make up the amount.
  * Return `-1` if the amount cannot be made up by any combination of the coins.

## Constraints

* Each coin denomination is a positive integer.
* You may assume an infinite number of coins for each denomination.
* The solution should aim for efficiency in time and space complexity.

## Concepts to Apply

* **Dynamic Programming (DP):** For computing optimal substructure and memoization.
* **Greedy Algorithms:** Inapplicable for arbitrary coin systems, but useful to compare.
* **Bottom-Up and Top-Down approaches:** Use both to explore time/space trade-offs.

## Deliverables

* A function or class implementation that solves the coin change problem.
* Test cases to validate the solution.
* Time and space complexity analysis.

## Example

```
Input: coins = [1, 2, 5], amount = 11
Output: 3
Explanation: 11 = 5 + 5 + 1

Input: coins = [2], amount = 3
Output: -1

