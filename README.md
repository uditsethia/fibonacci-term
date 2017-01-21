# fibonacci-term
fibonacci term in log of n time using recursion 
Nth fibonacci term is 
f(n)= f(n-1)+f(n-2)
On observation :
f(n)= f(2)*f(n-1)+f(1)*f(n-2)
further 
f(n)= f(r+1)*f(n-r)+f(r)*f(n-r-1)
where r is an integer less than n
this can be proved using mathematical induction
and to get it's maximum efficiency r should be floor of(n/2)
therefore f(n) can be computed in log(n) time along with memoization (dynamic programming)
