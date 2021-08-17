# CodingInterviewTips 👷‍♂️

### Disclamer: These are tips/tricks I learnt while doing interview questions on CodeSignal.com. I **don't** recommend solely studying from this document.


- *(Hashtables)*: Use hashtables(i.e sets in Python) to store intermediate steps in problems where steps are dependent on the output of the previous step. For example, I want to find all possible distinct sums of numbers in a list -> go through each number and add it to each "intermediate" value in the set.
- *(Binary Trees but can be extended generally)*: floor(index/2) will give you the index of the parent node if the indexing scheme start with 1 as the start node and increments from left to right down each level.
- *(Stacks and Recursion)*: When you feel you need to solve a problem recursively but need to abide by O(n) time complexity -> create a stack in Python with a list and use the pop and append commands to make a stack data structure -> also might be helpful to use the fact that when you access a item in list with "-1" you access the final item in the list.
- *(Heaps)*: Use heaps when we have to make lots of max/min comparisons in program.