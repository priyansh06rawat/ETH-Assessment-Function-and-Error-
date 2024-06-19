# ETH-Assessment-Function-and-Error
# Functions and Errors
In our Module 1 project of the ETH + AVAX PROOF: Intermediate EVM course by Metacrafter, we'll develop a smart contract utilizing the `require()`, `assert()`, and `revert` functions. These functions help enforce valid inputs, check internal state invariants, and handle error conditions gracefully. These functions are crucial for error handling in Solidity. Proper error management ensures the smart contract executes successfully and helps save users' gas by efficiently using the `revert` function.
# Error Handlers Used in Code
Require: Ensures certain conditions are met before executing a function.

In setGrade, it checks that only the admin can set grades and that grades are within a valid range.

In deleteStudent, it ensures only the admin can delete grades.

Revert: Stops the execution and reverts any changes made during the transaction if certain conditions are not met.

In getGrade, it checks if the student's grade exists.

Assert: Used to check for conditions that should never be false.

In updateAdmin, it ensures that the admin address is not the zero address.

# Introduction of code
This smart contract is designed to manage the grades of students in a decentralized way. Only an admin (usually the person who deployed the contract) can set and delete grades, ensuring that the data is controlled and secure.
# Author
Priyansh [@priyansh06rawat](https://github.com/priyansh06rawat)
# License
This project is licensed under the MIT license - see the license.md file for more details.
