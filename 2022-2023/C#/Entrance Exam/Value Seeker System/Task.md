The Value Seeker System searches out the best value bets each day from racings.

Every day you will receive coefficients from bets and they will be presented as a sequence of integers. First, you will
be given a series of integers representing the first set of bets. Afterwards, you will be given another sequence of
integers representing the second set of bets.

You need to start from the first bet in the first set and sum it with the last bet in the second set.

If the sum of their values is an even number, add the sum to your total result of the bets and remove the both
numbers from the sequences.

If the first set becomes empty print:
"First set is empty"
If the second set becomes empty print:
"Second set is empty"
In the end you need to determine the result of your bets. If the accumulated amount of the even sums is equal or
greater than 100, print:
"Your bets were amazing! Value: {accumulated amount of the even sums}"
Else print:
"Your bets were poor. Value: {accumulated amount of the even sums}"

Input
• On the first line, you will receive the integers representing the first set of bets, separated by a single space.
• On the second line, you will receive the integers representing the second set of bets, separated by a single
space.

Output
• On the first line of output – print which set of bets got empty in the format described above.
• On the second line – the result of your bets in the format described above.

Constraints
• All of the given numbers will be valid integers in the range [0, 100].
• There won’t be a case where the both sets become empty at the same time.

Examples

9 10 8 13 5 6         -  Second set is empty            Your bets were poor. Value: 40
0 4 7 4 5 22 4

40 40 60 10 99        -   First set is empty            Your bets were amazing! Value: 374
15 11 14 40 40 20
