# CSE-110-Lab-7-solution

Download Here: [CSE 110 – Lab 7 solution](https://jarviscodinghub.com/assignment/cse-110-lab-7-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

This lab is for practicing the object oriented programming, and you need to implement a Student Class and implement a simple system to modify and view user information.

Use the following Coding Guidelines:

• When declaring a variable, you usually want to initialize it.

• Use white space to make your program more readable.

• Use comments after the ending brace of classes, methods, and blocks to identify to which block it belongs.

 

Assignments Documentation:

At the beginning of each programming assignment you must have a comment block with the following information:

/*—————————————————————————

// AUTHOR:       (Put your name here)

// FILENAME:     Lab7.java

// SPECIFICATION:  This program is for practicing the object oriented programming.

// You need to develop the setName() method of Student Class and construct a simple system

// that can manage a student’s name and age

// LAB LETTER:  (Put your Lab Letter here)

//————————————————————————-*/

Getting Started

Create a class called Lab7. Use the same setup for setting up your class and main method as you did for the previous assignments. Be sure to name your file Lab7.java.

Hints

Please replace //–> with the correct program to finish the task according to the corresponding comment.

Please replace ??? with the correct program to enable the program to run as required.

 

//import anything you need

//–>

 

//declare the class Lab7

//–>

 

    //declare the main method

    //–>

 

 //Declare a scanner

 //–>

 

 // Declare a String username, an integer age  and Double course1, course2 and course3 to store marks obtained in 3 courses for 2 different student objects.

  //–>

 

 // Ask user to input a username for student 1

 //–>

 

 //Scan the input to username for student 1

 

 //–>

 

 

 // Ask user to input an age for student 1

 

 //–>>

 

 //read the integer to age for student 1

 

 String temp = scan.nextLine();

 age = Integer.parseInt(temp);

 

 

// Read marks obtained for 3 courses and store the values in , and

 

// Read marks for course1 and store in

 // Read marks for course2 and store in

// Read marks for course3 and store in

 

 // Repeat the above for Student 2

 

 // Instantiate 2 Student objects using its constructor method

 //–>

 

 // Declare Constant integers Print = 0, Modify_Username = 1, Modify_Age = 2, Average = 3, Quit = 4

 

  // Create an integer variable named choice.

  //–>

 

 

  // Create a do-while loop that exits only when the user chooses quit (choice = QUIT)

  // Have the do-statement here

  ??

  {

  // Print the following options:

  // “This proram does the following:”

  //–>

 

  // “0. Print information:”

  //–> 

  // “1. Modify username:”

  //–>  

  // “2. Modify age:”

  //–> 

  // “3. Compute Average:”

  //–> 

  // “4. Quit”

  //–>

  // Read the value the user enters and store it in an integer variable

   temp = scan.nextLine();

   choice = Integer.parseInt(temp);

  

  // Create a switch statement with as input for the 3 cases

   switch(???)

   {

   case ???:

    //print the String returned by toString() method of Student for student 1

    //–>

//print the String returned by toString() method of Student for student 2

    //–>

 

    //After each case, don’t forget to terminate it using break

    //–>

   case ???:

    //define a String variable

    //–>

                //Print “Enter the student number that you wish to midify: (1/2)?”

                //–>

                //scan the input integer and assign it to (based on this input you will modify the particular student’s info)

                //– >

               

    // Print “Please input the new name:”

    //–>

    //scan the String and assign it to

    //–>

    //call setName() method of student to replace the name with new input name

    //–>

   case mAge:

//Print “Enter the student number that you wish to midify: (1/2)?”

                //–>

                //scan the input integer and assign it to (based on this input you will modify the particular student’s info)

                // — >

    //define an int variable

    //–>

    // Print “Please input the new age:”

    //–>

    //scan the next integer and assign it to

    //–>

    //call setAge() method of student to replace the name with new input name

    //–>

 

   Case ???:

//Print “Enter the student number that you wish to midify: (1/2)?”

                //–>

                //scan the input integer and assign it to (based on this input you will modify the particular student’s info)

                // — >

               

                //Define a variable to store the average returned by the Average method

// Call the Compute Average method from Student class

                // Print the computed average

               

   case QUIT:

    // Print “You choose to quit”

    //–>

   default:

    // Print “Please choose again”

    //–>

   }

  }???

 }

}

 

 

Sample output:

Please input a username for student 1

wuliang

Please input an age for student 1

18

Please input marks for course 1 for student 1

56

Please input marks for course 2 for student 1

66

Please input marks for course 3 for student 1

76

 

 

Please input a username for student 2

Lee

Please input an age for student 2

21

Please input marks for course 1 for student 1

78

Please input marks for course 2 for student 1

88

Please input marks for course 3 for student 1

98

 

This program does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

0

Name is :wuliang

Age is                    :18

Name is :Lee

Age is                    :21

This program does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

1

Enter the student number that you wish to midify: (1/2)?: 1

Please input the new name:yoshi

This proram does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

0

Name is :yoshi

Age is                    :18

Name is :Lee

Age is                    :21

 

This proram does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

2

Enter the student number that you wish to midify: (1/2)?: 2

Please input the new age:22

This proram does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

0

Name is :yoshi

Age is                    :18

Name is :Lee

Age is                    :22

 

This program does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

3

Enter the student number that you wish to midify: (1/2)?: 2

Average for student 2 is 88

This program does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

5

Please choose again

This program does the following:

0. Print information:

1. Modify username:

2. Modify age:

3.Compute Average

4. Quit

3

You choose to quit
