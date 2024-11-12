# Bank-Safe

Bank Safe is a banking transaction deadlock prevention system designed to detect and prevent deadlocks in transaction sequences. It can identify potential deadlocks in a given list of transactions and propose a safe transaction order when possible. This project aims to improve transaction safety and maintain consistency in concurrent banking operations.

## Features

Deadlock Detection: Analyzes a list of transactions to detect potential deadlocks.

Safe Sequence Proposal: Suggests a safe sequence of transactions to avoid deadlocks.

Efficient Management: Helps manage banking transactions with a focus on safety and deadlock prevention.

## Tech Stack

C++: Core logic and algorithms

Linux: Development environment

File Systems: For managing transaction logs and records

Object-Oriented Programming (OOPS): Structure and modularity

## Usage

Input Transactions: The program accepts a list of banking transactions as input, typically formatted in a file.

Deadlock Detection: The program checks for potential deadlocks in the transaction list.

Safe Sequence Proposal: If a deadlock is detected, the program will suggest a safe order of transactions (if feasible) to prevent the deadlock.

## License

Distributed under the MIT License. See LICENSE for more information.
