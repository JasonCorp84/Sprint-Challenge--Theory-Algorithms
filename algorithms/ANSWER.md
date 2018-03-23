Exercise I. Give an analysis of the running time with respect to the input size n of each of the following
program fragments below:
a) a = 0;
while (a < n * n * n)
a = a + n * n;

This is a simple O(n) algorithm, since the number of steps required to run the algorithm is linear. With n = 5 input it takes 5 steps to run the program.
with n = 2, it takes 2 steps and so on. 

Exercise I.
b,

Sorry, but too many unknown variable for me. I am curious to see the solution.

Exercise I.
c,

n = (1-4) = 64  which is also the steps required// 4 different n
n = (5-16) = 128 which is also the steps req... // 12 different n
n = (17-36) = 192  // 20 different n
n = (37-64) = 256  // 28 different n

At this point it looks like the steps required are increasing by 64 and the input range is increasing by 8.
It looks like a liner line (on a graph it looks like stairs).

d,






