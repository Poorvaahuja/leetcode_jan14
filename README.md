# leetcode_jan14
LEETCODE PROBLEMS
## Q1 Circle and Rectangle overlapping
You are given a circle represented as (radius, xCenter, yCenter) and an axis-aligned rectangle represented as (x1, y1, x2, y2), where (x1, y1) are the coordinates of the bottom-left corner, and (x2, y2) are the coordinates of the top-right corner of the rectangle.
Return true if the circle and rectangle are overlapped otherwise return false. In other words, check if there is any point (xi, yi) that belongs to the circle and the rectangle at the same time.

<img width="441" alt="image" src="https://github.com/Poorvaahuja/leetcode_jan14/assets/122693422/552e59d3-05eb-464b-838e-e9c50a70561d">

## Q2 Determine if two strings are close
Two strings are considered close if you can attain one from the other using the following operations:
Operation 1: Swap any two existing characters.
For example, abcde -> aecdb
Operation 2: Transform every occurrence of one existing character into another existing character, and do the same with the other character.
For example, aacabb -> bbcbaa (all a's turn into b's, and all b's turn into a's)
You can use the operations on either string as many times as necessary.
Given two strings, word1 and word2, return true if word1 and word2 are close, and false otherwise.

<img width="437" alt="image" src="https://github.com/Poorvaahuja/leetcode_jan14/assets/122693422/48d041fe-1b22-4a04-a042-46d6a941b6dc">

## Q3 Find the winner of the circular game
There are n friends that are playing a game. The friends are sitting in a circle and are numbered from 1 to n in clockwise order. More formally, moving clockwise from the ith friend brings you to the (i+1)th friend for 1 <= i < n, and moving clockwise from the nth friend brings you to the 1st friend.
The rules of the game are as follows:
Start at the 1st friend.
Count the next k friends in the clockwise direction including the friend you started at. The counting wraps around the circle and may count some friends more than once.
The last friend you counted leaves the circle and loses the game.
If there is still more than one friend in the circle, go back to step 2 starting from the friend immediately clockwise of the friend who just lost and repeat.
Else, the last friend in the circle wins the game.
Given the number of friends, n, and an integer k, return the winner of the game.

<img width="400" alt="image" src="https://github.com/Poorvaahuja/leetcode_jan14/assets/122693422/7ae699ab-4b8b-4bac-8d13-57aeefe24bf6">
