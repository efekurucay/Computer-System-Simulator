# About
This project was created as part of an assignment or coursework for CSE102 Computer Programming. As a first-year Computer Engineering student, I developed this project to enhance my skills in software development and algorithm design.

If you're reviewing this project, your feedback or suggestions would be greatly appreciated. Thank you!

# Computer System Simulator

This project is a simple program that simulates a basic computer system. It demonstrates the operation of fundamental hardware components such as CPU, RAM, and Hard Disk.

## Features

- CPU simulation (speed, temperature, and usage tracking)
- RAM simulation (data writing/reading)
- Hard Disk simulation (file saving/reading)
- Basic computer operations:
  - Power On/Off
  - Run Program
  - Save File
  - Display System Status

## Usage

When the program is run, the desired operation is selected from the menu:

1. Power On: Starts the system
2. Power Off: Shuts down the system
3. Run Program: Loads a program into RAM and processes it on the CPU
4. Save File: Saves a file to the hard disk
5. Display System Status: Shows the status of all components
6. Exit: Terminates the program

## Technical Details

- Developed with Java 8
- Can be compiled using Maven
- Takes user input from the console
- Simulated system specifications:
  - 2000 MHz CPU
  - 1024 MB RAM
  - 500 GB Hard Disk

## Compilation and Execution

```bash
mvn clean compile
mvn exec:java -Dexec.mainClass="com.computer.Main"
```

## Author

Yahya Efe Kuruçay
