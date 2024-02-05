# impledge-technologies-Task
Word Composition Problem solution

# Explanation of the above Code

Step 1: We're using Dynamic Programming to solve this problem.

Step 2: First, sort the given words based on their lengths. If lengths are the same, sort them alphabetically.

Step 3: Start from the end of the list. Check if the current word can be formed by combining smaller words.

Step 4: If yes, store that word as ans1 and continue to find the second longest compounded word.

Step 5: Once you have both compounded words, store them as ans1 and ans2.

Step 6: Stop the process and print ans1 and ans2.

n: no. of strings k: maximum length of the string

# Time complexity:

Best case-> O(k^2) Average Case-> O(nk) Worst Case-> O(nk^2)

Space complexity: O(k)
