# RecurseCracklePop-in-Python
Write a program that prints out the numbers 1 to 100 (inclusive). If the number is divisible by 3, print Crackle instead of the number. If it's divisible by 5, print Pop. If it's divisible by both 3 and 5, print CracklePop. You can use any language.

#this is my solution in python.
print range(1,101)
def divisible(n):
	if n%5 ==0:
		print n
	elif n%5==0 and n%3 ==0:
		print "CracklePop."
	else:
		print "False"

print divisible(15)
