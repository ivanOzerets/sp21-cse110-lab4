## Part 1a:

    Question 1: values added: 20
    Question 2: final result: 20

    Question 3: values added: 20
    Question 4: ERROR. Variable 'result' is out of scope outside the if statement.

    Question 5: values added: 20
    Question 6: ERROR. Variable 'result' is out of scope outside the if statement.

## Part 1b:

    Question 1: The number '3' will be printed out. This is because 'var' gives a variable function scope 
    meaning it can be seen anywhere within the function. Thus, 'i' is accessed after the loop ends with a value of 3.
    
    Question 2: The number '150' will be printed out. This is because 'var' gives a variable function scope 
    meaning it can be seen anywhere within the function. Thus, 'discountedPrice' is accessed after the loop ends with a value of 150.

    Question 3: The number '150' will be printed out. This is because 'var' gives a variable function scope 
    meaning it can be seen anywhere within the function. Thus, 'finalPrice' is accessed after the loop ends with a value of 150.

    Question 4: This function will return an array of ints representing the discounted prices from the input. Specifically, the output
    would be [50, 100, 150]. This is because the loop just takes the inputs one by one and applies the 0.5 discount and does a round that
    does nothing to the current inputs. These discounted results are stored in the discounted array and returned.

    Question 5: ERROR. Variable 'i' would be out of scope outside the for loop.

    Question 6: ERROR. Variable 'discountedPrice' would be out of scope outside the for loop.

    Question 7: The number '150' will be printed out. This wount cause an error because the variable 'finalPrice' was created outside 
    of the for loop given the variable the function scope, letting it be seen anywhere in the function. Thus, 'finalPrice' is accessed 
    after the loop ends with a value of 150.

    Question 8: This function will return an array of ints representing the discounted prices from the input. Specifically, the output
    would be [50, 100, 150]. This is because the loop just takes the inputs one by one and applies the 0.5 discount and does a round that
    does nothing to the current inputs. These discounted results are stored in the discounted array and returned.

    Question 9: ERROR. Variable 'i' would be out of scope outside the for loop.

    Question 10: The number '3' would be printed out. The constant variable 'length' would be printed out which is just equal to the size
    of the array, that size being 3.

    Question 11: This function will return an array of ints representing the discounted prices from the input. Specifically, the output
    would be [50, 100, 150]. The fact that the variables are constants does not matter because a constant array data can still be modified.
    The constant inside the for loop is fine because it gets reassigened every loop cycle. These discounted results are stored in the
    discounted array and returned.

    Question 12: 
        
        A) student.name
        B) student["Grad Year"]
        C) student.greeting()
        D) student["Favotite Teacher"].name
        E) student.courseLoad[0]

    Question 13: 

        A) The string '32'. Arithmetic operations always try to be converted first to a string.
        B) The integer 1. Subtraction of char and int becomes int.
        C) The integer 3. null is always represented as 0;
        D) The string '3null'. Arithmetic operations always try to be converted first to a string, even for nulls.
        E) The integer 4. true is represented as 1 when added to an integer.
        F) The integer 0. false is represented as 0 and null is represented as 0 as well.
        G) The string is '3undefined'. Arithmetic operations always try to be converted first to a string.
        H) The value NAN. When subtracting undefined, the result will be NAN.

    Question 14: 

        A) true. Comparison operations try to compare integers so the char numbers get turned into ints.
        B) false. The character '2' is greater than the first char in '12' being '1'.
        C) true. Comparison operations try to compare integers so the char number '2' turns into an int.
        D) false. The === operator is a strict equality operator which checks equality without type conversion.
        E) false. true is represented as 1 which is not equal to 2.
        F) true. true is evaluated to 1 and Boolean(2) is evaluated to true because a Boolean convertion of any int but 0 is true.

    Question 15: The == is the equality operator that performs the standard equality test comparing if two values are equal while converting the data type to an equal type. The === is the string equality operator that performs an equality check without type conversion.

    Question 16: ** In the corresponding .js file **

    Question 17: The function modify array would return the array [2, 4, 6]. First I noticed that the callback variable in the modify array function is a reference to the doSomething function. The for loop loops through the array and at each index multiplies that value by 2 in the doSomething function then returns that array.

    Question 18: ** In the corresponding .js file **

    Question 19: 
    
        1
        4
        3
        2