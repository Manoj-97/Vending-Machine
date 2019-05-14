# Vending-Machine
The vending machine takes in five different denominations of coins and dispenses five different types of chocolates.
Vending machine takes input from the user regarding the choice of chocolate(s) and calculates the price.
Then takes coins as input and if the value of coins matches value of the chocolate(s),it dispenses the chocolate(s). 
After that, the machine checks to see if there is any change to be given back and if there is any, does the same.
This design was implemented using a simple FSM
	NICKEL: 5 cents
	DIME : 10 cents
	NICKEL_DIME : 15 cents
	DIME_DIME : 20 cents
	QUARTER : 25 cents 
Once the coin has been inserted and the chocolate has been chosen, the system validates it using the sensors and delivers the chocolates using the stepper motor and other sensors to the user. 
It also dispenses the required change using the same mechanism while displaying the details in the LCD screen.
A spartan 3E FPGA kit was used for implementation.
