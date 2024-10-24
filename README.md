# Lab-14-Prime-Numbers

In this lab, you will be determining how many factors a provided whole number has, whether the given value is PRIME or COMPOSITE, and displays the number of primes from 2 to the given number.

For this lab, you will be writing three METHODS in addition to the driver method (main).

Each static method needs to have documentation in this format.<br>
<i>
//  name of the method and a brief description.  Include any methods it relies upon (calls).<br>
// preconditions:  state the parameters that are being passed and what is expected of them<br>
// postconditions:  state what is being returned and what type it is.  If there are any special traits of the return value, state it here. </i>

<b>Be sure the headers of your methods match the headers below and perform as indicated.</b><br>

•	Write a static method <b>countFactors</b> that accepts an integer parameter and returns the number of factors of the integer.<br>
  –  Example	countFactors(24) returns 8 because  1, 2, 3, 4, 6, 8, 12, and 24 are factors of 24.

    public static int countFactors (int value){
		    //code you will write
    }

•	Write a static method <b>isPrime</b> which returns whether or not an integer is prime. This method must call <b>countFactors</b>.<br>
  -	  Example: isPrime(27) returns false and isPrime(47) returns true. 

    public static Boolean isPrime(int value) {
	    	//code you will write – must call countFactors
  	}

   
•	Write a static method <b>countPrimes</b> that accepts an integer parameter n and returns the number of primes from 2 to n (inclusive). This method must call <b>isPrime()</b>.<br>
–	Example:  countPrimes(24) returns 9 because 
2, 3, 5, 7, 11, 13, 17, 19, 23 are primes less than or equal to 24.

    public static int countPrimes(int n){
	    // code you will write – must call isPrime
	  }

The driver method should ask the user for an integer and return appropriate information.  See the sample output below.
1)	Use your program to compute how many prime numbers there are less than 5,000.
2)	Use your program to compute how many prime numbers there are less than 1,000,000. (This might take a while – try during off-peak time!)

 
 Sample run 1:<br>
  Enter an integer.<br>
   72<br>
  The number 72 has 12 factors.<br>
  72 is composite.<br>
  The number of primes from 2 to 72 is 20<br>

Sample run 2: <br>
      Enter an integer.<br>
      31<br>
      The number 31 has 2 factors.<br>
      31 is prime.<br>
      The number of primes from 2 to 31 is 11<br>


You come up with more tests that will test all unusual cases.

Requirements
•	Running program that asks the user for a whole number (do not need to error check)  and displays the number of factors, whether the number is prime or not, and the number of primes from 2 to the given number.<br>
•	Three static methods as described above.<br>
•	Documentation header<br>
•	Documentation for each method as descrived above<br>
•	Any additional documentation that would be useful for the reader of your code.

Small bonus opportunity:  Error check that the user entered a valid number.
