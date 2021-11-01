Comments:


/*  
multiline comments
* /



//single line comments less than screen size



1.	Remove commented out codes before handing in
2.	Remove unwanted comments before handing in (like endif, endfor)
3.	Write comments at the beginning of a block of comment.

Example:

//Prompting for grade input

//Output total and average grades

//Taking input for customer details

//Calculating trip cost

//Reading Blood donors details from donor.csv file

//Writing lunch menu details to lunch.csv file

4.	Do not write comments for every line.

5.	Remember you are writing comments for fellow programmers. So do not explain the meaning as you see in the programs done in the class for teaching/learning purpose.

6.	Comments are written to improve the readability of a program.

Example:

//Email validation
string email;
cout <<”\nEnter the email;”;
getline(cin, email);
intiI;
for (i=0;i<email.size();i++){
if ( email[i] == @){
//continue with other process
}
}
cout <<”\nNot a valid email”;


Naming convention: variables, structures and functions

1.  You can use meaningful and relevant, self- documented names using SnakeCase or camelCase or hyphenated-words.
Example:

string StudentName;  // Snake case
float lunchPrice; // Camel case
int loop-index; //hyphenated words

2. Do not use space while naming variables or functions or structures. 
3. Be consistent in the use of naming convention, you have chosen to follow in your group.
4. If for some reason, you have used a single character like i or j, for a temporary variable name, write a comment about it. Avoid using them, where possible. 


