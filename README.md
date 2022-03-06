# Stack Machine with Cool

| Command | Outcome                   |
|:-------:|---------------------------|
| _int_   | Push the number typed     |
| +       | Push the '+' signal       |
| s       | Push the 's' command      |
| e       | Evaluate the stack's head |
| d       | Prints the stack          |
| x       | Finishes the program      |

* The command __e__ will evaluate the top of the stack. That means:
    * If the top is '+', it will adds the two subsequent elements, pop them, and push the result into the stack;
    * If the top is 's', it will remove the 's' itself and switch the two following elements;
    * If the top is a number or the stack is empty, nothings happens.

This program has some assumptions:

* Only valid commands are entered by the user
* The numbers are all positive
