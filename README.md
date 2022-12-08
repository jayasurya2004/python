
def if_fibonacci(n):
	prev = 0
	next = 1
	while next < n:
		sum = prev + next
		prev, next = next, sum
		#print(prev, next)
	return n == next
		
print(if_fibonacci(20))
print(if_fibonacci)((15))
