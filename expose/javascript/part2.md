1. 3, i is declared with var and can be accessed from anywhere
2. 150, var variables can be accessed from any scope
3. 150, var varaibles can be accessed from any scope
4. [50, 100, 150], all variables are accessible since they were declared using var.
5. error, let is block-scoped and can only be accessible within the for loop.
6. error, let is block-scoped and can only be accessible within the for loop it was created.
7. 150, finalPrice was declared at the function level and can be used within the function it was created in.
8. [50, 100, 150], discounted was declared within the function and can be used within the function it was created in. The the other variables are only used within their respective blocks.
9. error, i is declared with let and can only be used within the for loop it was created in.
10. 3, length was initialled within the function and was not changed.
11. [50, 100, 150], the contents of the array can be modified with push.
12.
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13.
    a. '32', string concatenation with '3'
    b. 1, - forces '3' to be a number
    c. 3, null becomes a 0 and is added
    d. '3null', string concatenation with '3'
    e. 4, true turns into a 1 before adding
    f. 0, false turns into 0 and null turns into 0, then added
    g. '3undefined', string concatenation with '3'
    h. NaN, forces 3 to be a number but undefined can't be a number so it turns into NaN
14.
    a. true, '2' is converted into a number before comparison
    b. false, uses lexicograph comparison
    c. true, '2' is converted into a number before comparison
    d. false, === uses true comparison and sees that the number 2 is different from the string 2
    e. false, true becomes 1 and is not equal to 2
    f. true, boolean(2) becomes true and is strictly equal to true
15. == has loose equality where typing doesn't matter while === has strict equality where typing is accounted for
17. [2, 4, 6], it loops through the starting array while sending it through the doSomething() function. It pushes it to a new array before returning it after looping through.
19. 1 4 3 2