## Question 1
The value 3 will printed because there are three elements in the prices array, when calling discountPrices in line 19, so the for loop will stop when the variable i is equal to the length of the array which is 3.

## Question 2
The value 150 will be printed because it was the price that was added to the discount array, and the last element that was assigned to the discountPrice variable, with the value being 300*(1-0.5)=150.

## Question 3
The value 150 will be printed because the last value assigned to discountPrice is 150, and 150*100=15000, which when rounded is still the same, so dividing by 100 gives the original 150.

## Question 4
The function will return the array of prices, with each element being multiplied by 1 - 0.5, or rather discounted by 50%, so [100*0.5,200*0.5,300*0.5]=[50,100,150].

## Question 5
The code causes an error because the variable i that was declared in line 6 is now out of scope, so it is no longer accessible. Since the let keyword was used, the variable i is only accessible inside the for loop block.

## Question 6
The code causes an error because the variable discountedPrice that was declared in line 7 is no longer accessible. Since the let keyword was used, the variable discountedPrice is only accessible inside the for loop block.

## Question 7
The value 150 will be printed, since the rest of code runs as it should even though it is using the let keyword. The discountedPrice will still be calculated correctly, and the finalPrice will be assigned the rounded value of discountedPrice*100 divided by 100.

## Question 8
The function will return the array of prices, with each element being multiplied by 1 - 0.5, or rather discounted by 50%, so [100*0.5,200*0.5,300*0.5]=[50,100,150]. Using the let keyword does not change any of the calculations made. It simply changed the scope of the variables, but they were already only used within that scope.

## Question 9
This causes an error because i is a let keyword variable, so it is not accessible outside the for loop it was declared in.

## Question 10
The value 3 will be returned be the discountPrices function was called with an array of 3 elements as the prices value, and length is assigned the length of that array as its value.

## Question 11
The array [50,100,150] will be returned because each element in prices, is multipled by 0.5, and then pushed to the discounted array, so the oldest element pushed will appear first on the discounted array.

## Question 12
A. student.name

B. student['Grad Year']

C. student.greeting();

D. student['Favorite Teacher'].name

E. student.courseLoad[0]

## Question 13
A. The output is 32. Integers map to their string representation so 2 maps to '2', resulting in the string '32' being printed.

B. The output is 1. The minus sign is mathematical function that is used in integers, so '3' maps to 3, resulting in the result 3-2, or rather 1, being printed.

C. The output is 3. null is mapped to 0 to match 3 which is an integer, resulting in the output 3+0, or 3.

D. The output is 3null. '3' is a string, so null maps to the 'null' string, and the output is '3null'.

E. The output is 4. The plus sign function here involves an integer, so true maps to 1, and the output is 3+1, or 4.

F. The output is 0. false maps to 0 and null also maps to 0, so the sum is 0.

G. The output is 3undefined. '3' is a string, so undefined maps to 'undefined', and the output is '3'+'undefined', or '3undefined'.

H. The output is NaN. When involved in numeric conversions, undefined maps to NaN which always result in the output NaN.

## Question 14
A. The output is true since the '2' string becomes the number 2.

B. The output is false because they are both being compared as strings, so since the character 1, is less than the character 2 in terms of ASCII value.

C. The output is true since the string '2' becomes the number 2, so 2 is compared with 2, and they are both equal.

D. The output is false since the number 2 and the string '2' are different data types.

E. The output is false because when involved in numeric conversions, true maps to the number 1, which is not equal to 2.

F. The output is true because Boolean(2) converts the number 2 to a boolean value, and any number 

## Question 15
== operator only compares if the values are the same based on their values when converted to numbers, while the === operator does the same, but also checks if they were originally the same data type, so the === operator returns true only if the objects have the same data type and value.

## Question 16
In part2-question16.js file.

## Question 17
The modifyArray call in line 13 will return an array [2,4,6], but it is not assigned to any variable. Calling modifyArray with an array, and a function parameters will go through the following process:
1. It will create an empty array.
2. For every element in the array, the function in the function parameter is called with that element in the parameter, and the value that is returned from that function call will be pushed to the array previously created.
3. After iterating through all the elements in the array, the array created before, with the new elements if the array paremeter was not empty, will be returned.

## Question 18
In part2-question18.js file.

## Question 19
The output is:
1
4
3
2