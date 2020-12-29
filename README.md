# practice
nothing
hello!boys!
i am learning how to use github.
the_upper = 'QWERTYUIOPASDFGHJKLZXCVBNM'
the_lower = the_upper.lower()
print(the_lower)
the_number = '1234567890'
the_randint = the_upper + the_lower + the_number
print(the_randint,'length = ',len(the_randint))
code = ''
import random
for i in range(4):
	ran = random.randint(1,len(the_randint)-1)
	i1 = the_randint[ran:ran+1] 
	print(i1)
	code += i1
	print(code)
print('the verification code is :',code)
the_value = input('please write down the verification code ------>')
the_transformation1 = the_value.lower()
print(the_transformation1)
the_verification_code = code.lower()
print(the_verification_code)
if the_transformation1 == the_verification_code:
	print('you are right!')
else:
	print('you are wrong!')
