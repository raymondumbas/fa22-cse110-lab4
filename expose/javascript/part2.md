Question 1:
    Line 12 returns "3" because i is declared with var so it can be used in other blocks. The actual number 3 just refers to the length of prices whose value is to determine when to stop the for loop

Question 2:
    Line 13 returns "150" which is the discounted price of the last price in prices (since that is the last time discountedPrice is updated). That variable can be accessed outside of the block it is declared because the var declaration was used.

Question 3:
    Line 14 returns "150" the price of the last item of prices after rounding (since that is the last time "finalPrice" is updated). That variable can be accessed outside of the block it is declared because of the var declaration.

Question 4:
    This function will return a list of all of the values from prices after applying the given discount and rounding to match the dollar format.

Question 5:
    Line 12 causes an error because it tries to use the variable "i" that was declared with let, but it cannot because it is called outside of the block it was declared in.

Question 6:
    Line 13 causes an error because it tries to use the variable "discountedPrice" that was declared with let, but it cannot because it is called outside of the block it was declared in. 

Question 7:
    Line 14 will correctly output finalPrice because it is calling that variable in the same block that it was declared.

Question 8:
     This function will return a list of all of the values from prices after applying the given discount and rounding to match the dollar format.

Question 9:
    Line 11 will cause an error because it is trying to use "i" outside of the block that it was defined in, which is not allowed with the let declaration

Question 10:
    Line 12 will output "length". There is no error because length isn't changing and was declared in the same block.

Question 11:
    The function will return a list of prices after the given discount. Despite all of the const and let declaration, variables are new used outside of the block they were declared in, and there was no reassignment of a const variable without a new declaration.

Question 12:
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]

Question 13:
A.'32'   : the 2 is just concatenated after the 3
B. 1     : '3' is converted to an number then 3 minus 2
C. 3     : null is just treated as a zero when there is an number
D.'3null': first term is string, so + concatenates 'null'
E. 4     : true treated as 1, then 1 plus 3
F. 0     : false and null treated as zero, 0 + 0
G. '3undefined' : + after string concatenates, so undefined is just concatenated after 3
F. NaN   : - with an number will try to subtract but undefined is Not a Number

Question 14:
A. true  : '3' is converted to number
B. false : the first character of '12' is less than '2'
C. true  : '2' is converted to number
D. false : === does not convert '2' to a number
E. false : any value that's not 0, empty,etc. becomes true (ex. 2 )
F. true  : === does not convert '2' to bool but Boolean does

Question 15:
The primary difference is that == will convert types when appropriate to compare values.
But === is a strict equality operator, so it will not convert types

Question 17:
modifyArray([1,2,3] , doSomething) will return a new array where each number in the original array is multiplied by 2 (i.e. [2,4,6]). You can see that in the for loop, newArr is being pushed the callback with the current array item. Since doSomething is being passed as callback, now looking at doSomething, you can see all it does is return a number multiplied by 2.

Question 19:
1
4
3
2
