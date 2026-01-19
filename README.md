# Best Time to Buy and Sell Stock

## 🧠 Problem Idea
Given an array of prices where prices[i] is the price of a stock on the i-th day, choose one day to buy and another day in the future to sell to maximize profit.

## ✅ Approach
- Track the minimum price so far
- At each day, calculate profit if sold today
- Update maximum profit

## ⏱ Complexity
- Time: O(n)
- Space: O(1)

## 🧩 Pattern
Minimum so far + Best answer so far
