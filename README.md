Download Link: https://assignmentchef.com/product/solved-data-structures-and-algorithms-cs-f211-lab-sheet-4
<br>
<ol>

 <li>You go to the Egyptian market to get souvenirs for your friends and family. The market has weird rules. It has <strong><em>n</em></strong> different items numbered from <strong><em>1</em></strong> to <strong><em>n</em></strong>. Each item <strong><em>i</em></strong> has a <strong>base cost</strong> of <strong><em>a[i]</em></strong> Egyptian pounds. If you buy <strong><em>k</em></strong> different items with indices <strong><em>x<sub>1</sub>, x<sub>2</sub>, x<sub>3, </sub>…, x<sub>k</sub></em></strong> then the cost of each item is <strong><em>a[i]+x<sub>j</sub>*k </em></strong>where <strong><em>j</em></strong> varies from 1 to <strong><em>k</em></strong>. In other words, the cost of an item is equal to its base cost in addition to its index multiplied by the factor <strong><em>k</em></strong>.</li>

</ol>

You want to buy as many souvenirs as possible and your budget is <strong><em>S</em></strong> Egyptian dollars. Find the maximum number of items you can buy. In case the number of items is same, choose the one with the lowest total cost.




<strong>Input: </strong>

First line contains <strong><em>n</em></strong> and your total budget <strong><em>S</em></strong>.

Second line contains <strong><em>n</em></strong> different integers each of which denotes the cost of each item.

<strong>Output: </strong>

Two integers which denote the number of items and total cost you will be spending. <strong>Example: </strong>

3 14

2 3 5

<strong>Answer: </strong>

2 11

<strong>Explanation: </strong>

You cannot get 3 items because they will cost you [5,9,14] and the total cost would be 28. If you get 2 items, then the items would cost [4,7]. So, you can get items costing 4,7 which will cost you a total of 11 Egyptian dollars.




<ol start="2">

 <li>You are trying to solve questions for the DSA lab exam. The question set consists of a large number of different questions. You are exhausted today, so you decide to solve the problems like this:</li>

</ol>

You first solve <strong><em>v</em></strong> problems, the drink a cup of tea and solve floor(<strong><em>v/k</em></strong>) problems (where floor() function returns the largest possible integer value which is less than or equal to the given argument), then floor(<strong><em>v/(k*k)</em></strong> ), then floor(<strong><em>v/k*k*k</em></strong>) and so on…

The moment the value floor(<strong><em>v/(k^p)</em></strong> ) is equal to zero you stop and go to sleep. Find the minimum value of <strong><em>v</em></strong> such that you solve not less than <strong><em>n</em></strong> questions.




<strong>Input: </strong>

Two integers <strong><em>n</em></strong> and <strong><em>k</em></strong>.

<strong>Output: </strong>

Print only one integer – the minimum value of <strong><em>v</em></strong> that lets you solve <strong><em>n</em></strong> questions. <strong>Example: </strong>

7 2

<strong>Answer: </strong>

4

<strong>Explanation:  </strong>

When <strong><em>v</em></strong> = 4, then he solves the questions like this: 4, 2, 1.

Thus, he manages to solve 4+2+1 = 7 questions.




<ol start="3">

 <li>You are given a sorted list of elements. All of the elements in the array occur twice except for one element. Find the element that occurs only once.</li>

</ol>




<strong>Example: </strong>

1 1 4 4 5 6 6  <strong>Answer: </strong>

5




<ol start="4">

 <li>You and your friends are playing the game of stacking a pile of dominos. There are several towers of dominos each with some height. You are given with some initial configuration of the towers. To increase/decrease the height you need to add/remove the dominos. The number of dominos in the game remains the same. Adding/removing incurs a cost which is different for different towers. You are assigned with the task of making a set of towers such that all the towers have same height and the cost incurred is as minimum as possible. Note that the initial number of towers and final number of towers may not be the same.</li>

</ol>




<strong>Input:  </strong>

First line contains the number of towers.

Second line contains the number of dominos in each tower.

Third line contains the cost incurred for each tower when adding/removing a domino.

<strong>Output: </strong>

Minimum cost, number of towers, height of each tower <strong>Example: </strong>

3

1 2 3 10 100 200 <strong>Answer: </strong>

110, 2, 3

<strong> </strong>

<strong>Explanation: </strong>Remove a domino from Tower 1 (Cost 10) and add it to Tower 2 (Cost 100). Total cost is 110. Note that the number of dominos (6) remains the same, however, the number of towers has become 2 and the height of each tower is 3.

<strong> </strong>




<ol start="5">

 <li>You are working in a factory and you have <strong><em>n</em></strong> machines running simultaneously. Each of the machines takes a certain time (in secs) to produce an item. The time is different for different machines. Your task is to find the minimum time required to produce <strong><em>m</em></strong> items using Binary Search.</li>

</ol>




<strong>Input: </strong>First line contains <strong><em>n</em></strong> and <strong><em>m</em></strong>.

Second line contains an array which denotes how much each machine takes to produce an item.

<strong>Output: </strong>

Single integer denoting the minimum time to produce <strong><em>m</em></strong> items.  <strong>Example: </strong>

3 11

1 2 3

<strong>Answer: </strong>

6

<strong>Explanation: </strong>

In 6 secs, machine 1 will produce 6 items, machine 2 will produce 3 and machine 3 will produce 2.







<ol start="6">

 <li>Tony stark is lost in space and need to record his final message on a camera. As he was searching for the camera he found a secret scroll by Dr. Strange that had valuable information. The scroll key is a sum of two numbers whose absolute difference is equal to a number <strong><em>d</em></strong> on the scroll. Furthermore, those numbers can only be taken from a given set of <strong><em>n</em></strong> numbers on the scroll. If there is no key possible return the answer as -1 to Stark otherwise find the key. Solve this using binary search.</li>

</ol>




<strong>Constraints: </strong>

1&lt;=n&lt;=100000

1&lt;=d&lt;=10000

1&lt;=Number on Scroll&lt;=10000




<strong>Input:</strong>

This line contains integer <strong><em>n</em></strong>

This line contains the array of integers on the scroll

This line contains the absolute difference <strong><em>d</em></strong>




<strong>Sample Input: </strong>

6

5 20 3 2 50 80

78




<strong>Sample Output: </strong>

82




<strong>Sample Input: </strong>

6

5 220 13 122 550 80

23




<strong>Sample Output: </strong>

-1




<ol start="7">

 <li>Senti and Panda are best friends. Senti loves cocktails. Senti has decided to rank his favourite <strong><em>n</em></strong> cocktails based on their price. Panda as a prank decided to swap two adjacent numbers on the ranked order. Senti got very emotional after that and asked his friend Moggie to order a drink for him for <strong><em>k</em></strong> price and also tell him its current rank on the new list. Help Moggie to find the current rank. If it is not there on the list return -1. Solve this problem using binary search.</li>

</ol>




<strong>Constraints: </strong>

1&lt;=n&lt;=100000

1&lt;=k&lt;=10000

1&lt;=Price of a cocktail&lt;=10000




<strong>Input: </strong>

This line contains integer n

This line contains an updated price list

This line contains k




<strong>Sample Input: </strong>

7

3  10 40 20 50 70 80

40




<strong>Sample Output: </strong>

3




<strong>Sample Input: </strong>

6

51 221 131 1222 5550 8000

123




<strong>Sample Output: </strong>

-1







<ol start="8">

 <li>Jon Snow likes Ygritte and decided to propose her. As Ygritte is very shrewd, she decided to give him a task. She gives him a sorted list of <strong><em>n</em></strong> numbers and rotates it several times. She now asked him to find the position of number <strong><em>k</em></strong> on the list as fast as possible. Help him to find the love of his life. Solve this problem using binary search. Assume that index starts from 1.</li>

</ol>




<strong>Constraints: </strong>

1&lt;=n&lt;=100000

1&lt;=k&lt;=10000

1&lt;=number on the list&lt;=10000




<strong>Input: </strong>

This line contains integer <strong><em>n</em></strong>

This line contains numbers on the list

This line contains <strong><em>k</em></strong>




<strong>Sample Input: </strong>

5

4 5 1 2 3

3




<strong>Sample Output: </strong>

5




<strong>Sample Input: </strong>

5

2 4 6 0 1

6




<strong>Sample Output: </strong>

3







<ol start="9">

 <li>Naruto and Sasuke are on a mission of finding number <strong><em>k</em></strong> among <strong><em>n</em></strong> numbers or inserting them. Naruto does the job of finding the number and if it is not there then Sasuke inserts it at the apt position. They need to do it as quickly as possible. Help them to solve in O(<strong><em>log n</em></strong>) time using binary search. Also, provide the name of the person who did the last action. Assume that index starts from 1.</li>

</ol>




<strong>Constraints: </strong>

1&lt;=<strong><em>n</em></strong>&lt;=100000

1&lt;=number on the list&lt;=10000

1&lt;=<strong><em>k</em></strong>&lt;=10000




<strong>Input: </strong>

This line contains integer <strong><em>n</em></strong>

This line contains numbers on the list

This line contains <strong><em>k</em></strong>




<strong>Sample Input: </strong>

4

1 3 5 6

5




<strong>Sample Output: </strong>

Naruto 3




<strong>Sample Input: </strong>

4

1 3 5 6

2




<strong>Sample Output: </strong>

Sasuke 2




<ol start="10">

 <li>Kevin Durant is trying to play the game of odd numbers. He is being given an array of <strong><em>n</em></strong> numbers where all elements appear even number of times except one. All repeating occurrences of elements appear in pairs and these pairs are not adjacent (there cannot be more than two consecutive occurrences of any element).</li>

</ol>

Find the element that appears an odd number of times.<strong>                                                                                         </strong>




<strong>Constraints: </strong>

1&lt;=n&lt;=100000

1&lt;=number on the list&lt;=10000




<strong>Input: </strong>

This line contains integer n

This line contains numbers on the list




<strong>Sample Input: </strong>

15

1 1 2 2 1 1 2 2 13 1 1 40 40 13 13




<strong>Sample Output: </strong>

13




<strong>Sample Input: </strong>

13

1 1 2 2 3 3 4 4 3 600 600 4 4




<strong>Sample Output: </strong>

3




****************************