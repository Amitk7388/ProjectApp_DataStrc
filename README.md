This app is used to convert ASCII number to original numbers which was asked in interview and it was comppleted by me.
-|
_|_       => to 1

above fromat you will and then this number will get converted into the original number and if number cannot be identified then it will give ? mark and it wil jumb to the ext number 

User Story 1 - Parse invoice numbers
We have recently decided to digitise our old invoice archives. Since finding a volunteer for such an arduous task was impossible, an employee was selected at random and instructed to type in all invoice numbers into a text file.

Little did we know that the employee we picked is an aspiring ASCII artist. Instead of handing us a file containing a set of numbers, we ended up with 7-segment display representations of the invoice numbers.

This is where you come in. Write a simple node service that allows the user to upload a text file of 7-segment invoice numbers, and outputs a list with the parsed invoice numbers.

Input:

A text file containing several hundreds of invoice numbers in the following form:

      _  _     _  _  _  _  _  (line 1)
    | _| _||_||_ |_   ||_||_| (line 2)
    ||_  _|  | _||_|  ||_| _| (line 3)
                              (line 4)
      _  _  _  _  _  _     _  (line 5)
  |_||_|| ||_||_   |  |  ||_  (line 6)
    | _||_||_||_|  |  |  | _| (line 7)
                              (line 8)
Invoice number format:

Each invoice number is constructed of 9 digits [0..9]
Invoice number is written using _ and | characters.
Invoice number input takes 4 lines.
The first 3 lines contain 27 characters.
The fourth line is blank.
Note: You can use input_user_story_1.txt to feed your program.

Output:

A text file with the parsed invoice numbers. One number per row.

Example:

  123456789
  490867715
Note: You can use output_user_story_1.txt to test that the output file generated by your program is correct.

User Story 2 - Top Secret
During your in-person interview, you will be asked to modify your code to handle User Story 2. So be sure your code can be easily modified. More details will be given during the interview.

Input:

Example:


      _  _     _  _  _  _  _  (line 1)
    | _| _||_||_ |_   ||_||_| (line 2)
    ||_  _|  | _||_|  ||_| _| (line 3)
                              (line 4)
      _  _  _  _  _  _     _  (line 5)
  |_||_|| ||_||    |  |  ||_  (line 6)
    | _||_||_||_|  |     | _| (line 7)
                              (line 8)
Output:

Example:


  123456789
  4908?7?15 ILLEGAL
