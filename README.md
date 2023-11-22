# Lint Hub Virtual Coffee Machine
Lint Hub Virtual Coffee Machine is a Python program designed to emulate the functionality of a physical coffee machine. This virtual machine allows users to choose from a variety of drinks, insert coins for payment, and receive their desired beverages. The program also provides a report on the current resources and allows for maintenance operations.

Instructions for Use
Follow these steps to interact with the Lint Hub Virtual Coffee Machine:

Prompt User for Drink Selection:

Enter your choice by typing "espresso," "latte," or "cappuccino" when prompted: "What would you like? (espresso/latte/cappuccino):"
The prompt will appear after each action is completed, allowing you to serve the next customer.
Turn Off the Coffee Machine:

To turn off the coffee machine, enter "off" when prompted.
The secret word "off" is used to end the execution of the program.
Generate Report:

Enter "report" when prompted to generate a report displaying current resource values:
makefile
Copy code
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5
Check Resources Sufficiency:

The program checks if there are enough resources to make the selected drink.
If resources are insufficient, a message is displayed (e.g., "Sorry, there is not enough water").
Process Coins:

If there are sufficient resources, insert coins as prompted.
Quarters = $0.25, dimes = $0.10, nickels = $0.05, pennies = $0.01.
The program calculates the monetary value of the inserted coins.
Check Transaction Success:

Verify if the user has inserted enough money for the selected drink.
If successful, the cost of the drink is added to the machine's profit.
Change is provided if the user inserted too much money.
Make Coffee:

If the transaction is successful and there are enough resources, the ingredients are deducted.
A message is displayed (e.g., "Here is your latte. Enjoy!").
Example Scenario
Suppose a latte is chosen, and the user inserts the correct amount of money:

Report before purchasing latte:

makefile
Copy code
Water: 300ml
Milk: 200ml
Coffee: 100g
Money: $0
Report after purchasing latte:

makefile
Copy code
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5
