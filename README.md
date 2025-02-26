Download Link : https://programming.engineering/product/remodeling-a-daycare-answered/

# Remodeling-a-Daycare-Answered
Remodeling a Daycare Answered
You administer an infant daycare that has n rooms lled with babies (so many babies!). Each room has a capacity Ci, denoting how many children can legally t into that room. In addition, each room is lled to capacity every single day during work hours (business is good!). You’ve recently decided to remodel the entire building one room at a time, but there are some constraints. Every remodeled room takes 24 hours, and you need to move the children from the remodeled room temporarily for that day. Addi-tionally, once a room is successfully remodeled, the capac-ity of that room might go up or down (or possibly stay the same). We’ll call the new capacity of the i’th room Ci0 .

The problem you must solve then is this: you need to purchase a temporary trailer to hold extra children during remodeling days, but the trailer company charges based on the child capacity of the trailer. Can you gure out the minimum capacity extra trailer necessary in order to fully remodel the daycare successfully?

Let’s look at an example. Suppose the daycare has four rooms A, B, C, and D with capacities 6, 1, 3, and 3. The new capacities after remodeling each room will become 6, 7, 5, and 5 respectively. If you buy a trailer with a capacity of 1 child, you can move the child from room B there for one day and that room’s new capacity become 7. You can keep the one child in the trailer, move 6 children into room B while you remodel room A. You can then continue to use room B as extra space while remodeling rooms C and D. Notice that for this problem 1) children do NOT need to end up in the same room they started in after the remodeling is nished and 2) you may no longer have enough space to hold all of the original children and the extra trailer may need to become permanent (we’ll call this case one of terrible planning on your part).

Input

The input le contains several test cases, each in the following format: The input begins with a line containing one integer n (1 n 106 ), which is the number of rooms in your daycare. Following this are n lines, each describing a room as two integers Ci and Ci0 , the capacity of each room currently and the capacity of that room after remodeling.

Output

For each test case, display the total extra capacity (in number of children) you must purchase (print this value on a line by itself).

Hint

This is a di cult problem, but you have one HUGE hint to help you. The solution will be some kind of greedy algorithm. Make sure to create many test cases to test your di erent approaches as you develop them.

Sample Input

4
		

6
	

6
	

1
	

7
	

Sample Output

3
	

5
	

3
	

5
	

1

4
		

5

2
	

2
	

3
	

3
	

    1

    10

Solution
