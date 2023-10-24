# javascript-typescript-piaic-atm

# Simple ATM Machine Simulator

This is a simple command-line ATM machine simulator implemented in JavaScript using the `inquirer` library for user input. The simulator allows users to perform basic ATM functions such as withdrawals, balance checks, and deposits. It uses randomly generated user data and simulates interactions with an ATM machine.

## How to Use

1. Clone this repository to your local machine.

2. Ensure you have Node.js installed.

3. Install the required dependencies using the following command:

   ```bash
   npm install
4. Run the ATM simulator using the following command:
  
   ```bash
   node index.js
5. You will be prompted to enter a PIN code. The simulator uses randomly generated user data, and you can enter PIN codes from 1000 to 1004 to simulate different users.
6. After entering the PIN code, you can choose from various ATM functions, including withdrawals, balance checks, deposits, and exiting the simulator.
7. The simulator provides feedback and simulates the selected ATM function. You can continue to perform ATM transactions by re-running the program.

## Code Structure

1. The code generates random user data, including user ID, PIN code, name, account number, and balance.
2. The <b>'inquirer '</b> library is used to capture user input and simulate interactions with the ATM machine.
3. The code includes functions for performing ATM functions, including withdrawals, balance checks, deposits, and exiting the simulator.
4. User data is stored in an array, and user data is retrieved based on the entered PIN code.
5. The simulator provides feedback for each transaction, such as displaying the withdrawn amount, balance, and more.
6. The code is structured to be interactive and user-friendly, allowing users to simulate ATM transactions with ease.

## Dependencies
. <b>inquirer</b>: For capturing user input.

## Author
Nazneen Akram

