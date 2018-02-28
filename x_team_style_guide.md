# X-Team 03 Style Guide

The 4 C's. Consistancy, Clarity, Concise, Camel.

## Naming conventions

Camel Case.

### Examples
* interfaces
 ExampleInterface
* classes
 ExampleClass
* exception types
 ExampleExceptionException
* fields
 exampleField
* methods
 exampleMethod
* parameters
 exampleParameter
* local variables
 exampleLocalVariable
* instance constants
 EXAMPLE_CONSTANT
* class constants
 EXAMPLE_CONSTANT

## Commenting style for public and private members of a class or interface:

Class headers, file headers, method headers, and comments on confusing parts of code.

### Examples

* classes

    //////////////////// ALL ASSIGNMENTS INCLUDE THIS SECTION /////////////////////
    //
    // Title:           (descriptive title of the program making use of this file)
    // Files:           (a list of all source files used by that program)
    // Course:          (course number, term, and year)
    //
    // Author:          (your name)
    // Email:           (your @wisc.edu email address)
    // Lecturer's Name: (name of your lecturer)
    //
    //////////////////// PAIR PROGRAMMERS COMPLETE THIS SECTION ///////////////////
    //
    // Partner Name:    (name of your pair programming partner)
    // Partner Email:   (email address of your programming partner)
    // Lecturer's Name: (name of your partner's lecturer)
    // 
    // VERIFY THE FOLLOWING BY PLACING AN X NEXT TO EACH TRUE STATEMENT:
    //   ___ Write-up states that pair programming is allowed for this assignment.
    //   ___ We have both read and understand the course Pair Programming Policy.
    //   ___ We have registered our team prior to the team registration deadline.
    //
    ///////////////////////////// CREDIT OUTSIDE HELP /////////////////////////////
    //
    // Students who get help from sources other than their partner must fully 
    // acknowledge and credit those sources of help here.  Instructors and TAs do 
    // not need to be credited here, but tutors, friends, relatives, room mates 
    // strangers, etc do.  If you received no outside help from either type of 
    // source, then please explicitly indicate NONE.
    //
    // Persons:         (identify each person and describe their help in detail)
    // Online Sources:  (identify each URL and describe their assistance in detail)
    //
    /////////////////////////////// 80 COLUMNS WIDE ///////////////////////////////

* fields

     //Comment like this

* constructors

     /**
      * Multiple lines of Javadoc text are written here,
      * wrapped normally...
      * <p>
      * This is the start of a new paragraph!
      */
 
* methods

    /**
     * Multiple lines of Javadoc text are written here,
     * wrapped normally...
     * <p>
     * This is the start of a new paragraph!
     */
 
* coding style (brackets, horizontal, and vertical spacing) for:

  * if statements
        if(x>=y){
           some code
        }
    
  * switch statement
  
       We will not use these
 
 * while loops
 
     while(something){
        code
     }
  
  * for loops
  
        for(int i = 0; i < something; i++{
             some code
        }
        
  * enhanced for loops
  
         use when you can, follow same format as for loops.
