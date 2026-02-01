# program-to-print-Fibonacci-series-using-iteration
a = 0
b = 1
n=int(input(&quot;Enter the number of terms in the sequence: &quot;))
print(a,b,end=&quot; &quot;)
while(n-2):
c=a+b
a,b = b,c
print(c,end=&quot; &quot;)
n=n-1
