# fibonacci-term<br />
fibonacci term in log of n time using recursion <br />
Nth fibonacci term is <br />
f(n)= f(n-1)+f(n-2)<br />
On observation :<br />
f(n)= f(2)*f(n-1)+f(1)*f(n-2)<br />
further <br />
f(n)= f(r+1)*f(n-r)+f(r)*f(n-r-1)<br />
where r is an integer less than n<br />
this can be proved using mathematical induction<br />
and to get it's maximum efficiency r should be floor of(n/2)<br />
therefore f(n) can be computed in log(n) time along with memoization (dynamic programming)<br />
