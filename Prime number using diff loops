#prime numbers in given range
#using while in for
def prime_range1(x,y):
	for num in range(x,y+1):
		i=1
		count=0
		while i<num//2+1:
			if num%i == 0: count+=1
			i+=1
		if count==1: print(num)

#using for in while
def prime_range2(x,y):
	num=x
	while num<y+1:
		count=0
		for i in range(1,num//2+1):
			if num%i == 0: count+=1
		if count==1: print(num)
		num+=1

#using while in while
def prime_range3(x,y):
	num=x
	while num<y+1:
		i=1
		count=0
		while i<num//2+1:
			if num%i == 0: count+=1
			i+=1
		if count==1: print(num)
		num+=1
#user input
x,y=int(input()),int(input())
prime_range3(x,y)
