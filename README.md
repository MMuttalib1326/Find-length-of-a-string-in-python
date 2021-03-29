# Find-length-of-a-string-in-python
Python Programming

def findLen(str):
	counter = 0
	while str[counter:]:
		counter += 1
	return counter

str = "Mohd Muttalib"
print(findLen(str))


