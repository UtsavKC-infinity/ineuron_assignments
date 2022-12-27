					Ques.no.1.Ans
The two values of the boolean data type is True and False. We can evalute  the boolean value  by using some conditional operator like 10>5 , 10==10 , 10<20 , 20 != 10 and we can directly also assign boolean value by using assignment operator to varaible like  is_true = True.
					

					Ques.no.2.Ans
The three different types of Boolean operators are:
1)and
2)or
3)not
					

					Ques.no.3.Ans
1)and operator table:
True + True => True
True + False => False
False + True => False
False + False => False
2) or operator table:
True + True => True
True + False => True
False + True => False
False + False => False
3) not operator table:
True => False
False => True
					

					Ques.no.4.Ans
(5 > 4) and (3 == 5) . It gives False value.
not (5 > 4). It gives False value.
(5>4) or (3 == 5). It gives True value.
not ((5 > 4) or (3 == 5)). It gives False value.
(True and True) and (True == False). It gives False value
(not False) or (not True). It gives True value.
				
					
					Ques.no.5.Ans
The six comparison operators are:
greater than (>)
greater than equal to (>=)
less than (<)
less than equal to (<=)
equal to (==)
not equal to (!=)

					
					Ques.no.6.Ans
The difference between equal to and assignment operator is that the equal to operator use two equal operator sign i.e "==" but assignment operator only use one equal to sign. Equal to operator is used to conditions checking wheres assignment operator is used to assign value to the variable.
Condition for equal to operator:
-use to compare two values and variables.
Eg : 10==10 , "RAM" ==  "RAM"
Condition for assignment operator:
-use to assign value to variables
Eg: user_name = "RAM"
					

					Ques.no.7.Ans
After successfully execution of code we will obtain:
ham
spam
spam
					
					
					Ques.no.8.Ans
spam = int(input("Enter the number: "))
if spam == 1:
    print("hello")
elif spam == 2:
    print("Howdy")
else:
    print("Greetings!")
					

					
					Ques.no.9.Ans
If my programme is stuck in an endless loop , i will use "ctl + c" key to terminate the endless loop situation.
					

					Ques.no.10.Ans
The difference between break and continue is given below in points:
break keyword is use to help the program to get  terminate from running loop whereas continue keyword is use to escape particular condition without terminating the loop
the stament which is write below the break keyword will not execute once the break keyword execute but in continue keyword whatever the statement we write in below of continue keyword will execute by avoiding the conditions where we write continue keyword
break keyword minimize the risk of getting infinte loop condition but in case of continue keyword infinite loop may occur .

					
					Ques.no.11.Ans
In a for loop, the difference between range(10), range(0, 10), and range(0, 10, 1)  are:
range(10) => in this build in function , only the end index is define upto which the loop will run . Even though there is no start index but by default python will iterate the objects from 0 index to last index which is 9 in our case 
range(0,10) => in here , loop will run upto 0 index to 9 index i.e range(start from, end to). 
range(0,10,1) => in here, we can see range(start from, end to, step) which means our loop will run from 0 index and it will end when it reach to 9 index and while loop run from 0 to 9 , it will jump step 1 in every attempt of iteration.
					
					
					Ques.no.12.Ans
Print 1 to 10 using for loop is :
	for n in range(0, 10):
    		print(n+1)
Print 1 to 10 using while loop is : 
	n = 0
	while n < 10:
    		print(n+1)
    		n += 1
					
					

					Ques.no.13.Ans
If I had a function named bacon() inside a module named spam, I would call it after importing spam which is possbile  by using the name of the module as a prefix, followed by the name of the function
 