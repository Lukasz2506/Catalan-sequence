'''Program which types all of the Catalan sequence for the numbers from 1 to a million.
It prints information about how many numbers are even and how many are odd in this sequence'''

# definition able to count factorial from the value

def factorial (value):
    factorial = 1
    for number in range (1, value + 1):
        factorial = factorial * number
    return factorial

print()

listCat = []
value = 1
Cat = 0

while Cat < 1000000:
    Cat = factorial(2*value)/(factorial(value+1)*factorial(value))
    value += 1
    if Cat < 1000000:
        listCat.append(Cat)
    

print("The Catalan sequence with all the numbers lower than a million: ", "\n" , listCat)

print()

evenElements = [element for element in listCat if element % 2 == 0]
print("Even Catalan numbers lower than a million: ", "\n", evenElements)

print()

oddElements = [element for element in listCat if element % 2 != 0]
print("Even Catalan numbers lower than a million: ", "\n", oddElements)

