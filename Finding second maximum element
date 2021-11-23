#finding second max element in alist
def large(a):
	max=a[0]
	for num in a:
		if num>max: max=num
	return max
def second_large(a):
	max=large(a)
	a.remove(max)
	return large(a)

a=[2,8,4,3,6,37]
second_max=second_large(a)
print(second_max)
