Counting Pairs:
Two pairs of integers (a, b) and (c, d) are considered distinct if
at least one element of (a, b) ∉ (c, d). For example given a list
(1, 2, 2, 3), (1, 2) is distinct from (1, 3) and (2, 3) but not from
(1, 2) with 2 chosen from a different index in the list. A pair is
valid if a ≤ b.
You will be given an integer k and a list of integers. Count the
number of distinct valid pairs of integers (a, b) in the list for
which a + k = b.

INPUT:

Enter No of array Elements:

4

Enter the Elements:

1
1
1
2

Enter the difference:

1


OUTPUT:

count:1


MinimumUniqueArray:
Given an array, you must increment any duplicate elements
until all its elements are unique. In addition, the sum of its
elements must be the minimum possible within the rules. For
example, if arr = [3, 2, 1, 2, 7], then arr = [3, 2, 1, 4, 7]
and its elements sum to a minimal value of 3 + 2 + 1 + 4 + 7 =
17.

INPUT:
Enter No of array Elements:
3
Enter the Elements:
1
2
2
OUTPUT:
Sum:6

StackOperations:
Implement a simple stack that accepts the following commands and performs the operations associated with them:
push k : Push integer k onto the top of the stack.
pop : Pop the top element from the stack.
inc e k : Add k to each of the bottome elements of thestack.

After every command, print the top of the stack.

INPUT and OUTPUT FORMAT:
Enter No of Operations:
6
Enter the Operations:
push 4
4
push 2
2
push 1
1
inc 2 1
1
pop
3
pop
5

