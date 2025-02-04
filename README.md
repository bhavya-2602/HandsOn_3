# function x = f(n)
x = 1;
for i = 1:n
for j = 1:n
x = x + 1;

3.Find polynomials that are upper and lower bounds on your curve from #2. From this specify a big-O, a big-Omega, and what big-theta is.
Ans.
The fitted curve is a quadratic function of the form y = ax^2 + c. Big-O: O(n^2).This means that the runtime is bounded above by a constant multiple of n^2 for sufficiently large n.
Big-Omega:Ω(n^2).This means that the runtime is bounded below by a constant multiple of n^2 for sufficiently large n.
Big-Theta:Θ(n^2).This means that the runtime is asymptotically equivalent to n^2.

If I modified the function to be:
x = f(n)
x = 1;
y = 1;
for i = 1:n
for j = 1:n
x = x + 1;
   y = i + j;

4. Will this increate how long it takes the algorithm to run (e.x. you are timing the function like in #2)?
Ans. Newly add operation (y = i + j) in inner loop has constant time complexity of O(1).So,it will not significant impact on runtime of function.

6. Will it effect your results from #1?
Ans. The changes will not affect the overall runtime complexity of the function. It remains O(n^2), Big-Omega(n^2), and Big-Theta(n^2).
