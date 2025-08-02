# ATM-Simulator-Java 

A console-based **ATM Simulation** program written in Java that allows users to perform banking operations like balance inquiry, cash deposit, withdrawal, and viewing a mini statement. It demonstrates Object-Oriented Programming concepts such as interfaces, encapsulation, and class design.

## Features 

- User authentication with ATM number & PIN
- View current account balance
- Withdraw money (in multiples of 500)
- Deposit money into the account
- View mini statement (transaction history)
- Exit gracefully with thank-you message

## Technologies Used 

Java  
IntelliJ IDEA  
Command Line (Terminal)

## How to Run 

Clone the repository:  
`git clone https://github.com/ananthakrishnan234/ATM-Simulator-Java.git`

Navigate to the project folder:  
`cd ATM-Simulator-Java`

Compile and run the Java files:  
```bash
javac src/*.java
java -cp src Main
```

> Default ATM Number: `12345`  
> Default PIN: `123`

## Folder Structure 

ATM-Simulator-Java/  
├── src/  
│   ├── Main.java        # Entry point of the application  
│   ├── ATM.java         # Account balance model class  
│   ├── AtmOperationInterf.java # Interface for ATM operations  
│   └── AtmOperationImpl.java  # Business logic implementation  
├── .gitignore         # Git ignored files/folders  
├── out/              # Compiled classes  
└── .idea/             # IDE project config files

## Sample Session 

```
Welcome to ATM Machine !!!
Enter Atm Number : 12345
Enter Pin: 123
1.View Available Balance
2.Withdraw Amount
3.Deposit Amount
4.View Ministatement
5.Exit
Enter Choice :
```

## Author 

[Ananthakrishnan Sudhakaran](https://github.com/ananthakrishnan234)

## License 

This project is open-source and available under the [MIT License](LICENSE).
