

# Lint Hub Virtual Coffee Machine

Lint Hub Virtual Coffee Machine is a Python program designed to simulate the operation of a physical coffee machine. This virtual machine allows users to choose from a variety of drinks, insert coins for payment, and receive their desired beverages. Additionally, the program provides a detailed report on the current resources and supports maintenance operations.

## Project Purpose and Success

The primary goal of the Lint Hub Virtual Coffee Machine project was to create a Python program that emulates the functionality of a physical coffee machine. This virtual machine allows users to interactively choose their preferred drinks, make payments, and receive beverages, all within a simulated environment.

The successful implementation of the project demonstrates the ability of the program to accurately handle user input, manage resources, and provide a seamless coffee-ordering experience. By following the outlined instructions, users can navigate through the virtual coffee machine, making selections and receiving reports on resource levels.

## Instructions for Use

Follow these steps to interact with the Lint Hub Virtual Coffee Machine:

1. **Prompt User for Drink Selection:**
   - Enter your choice by typing "espresso," "latte," or "cappuccino" when prompted: "What would you like? (espresso/latte/cappuccino):"
   - The prompt will appear after each action is completed, allowing you to serve the next customer.

2. **Turn Off the Coffee Machine:**
   - To turn off the coffee machine, enter "off" when prompted. The secret word "off" is used to end the execution of the program.

3. **Generate Report:**
   - Enter "report" when prompted to generate a report displaying current resource values:

     ```makefile
     Water: 100ml
     Milk: 50ml
     Coffee: 76g
     Money: $2.5
     ```

4. **Check Resources Sufficiency:**
   - The program checks if there are enough resources to make the selected drink. If resources are insufficient, a message is displayed (e.g., "Sorry, there is not enough water").

5. **Process Coins:**
   - If there are sufficient resources, insert coins as prompted. Quarters = $0.25, dimes = $0.10, nickels = $0.05, pennies = $0.01. The program calculates the monetary value of the inserted coins.

6. **Check Transaction Success:**
   - Verify if the user has inserted enough money for the selected drink. If successful, the cost of the drink is added to the machine's profit. Change is provided if the user inserted too much money.

7. **Make Coffee:**
   - If the transaction is successful and there are enough resources, the ingredients are deducted. A message is displayed (e.g., "Here is your latte. Enjoy!").

## Example Scenario

Suppose a latte is chosen, and the user inserts the correct amount of money:

- **Report before purchasing latte:**

  ```makefile
  Water: 300ml
  Milk: 200ml
  Coffee: 100g
  Money: $0

 - **Report after purchasing latte:**
 ``` Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5










