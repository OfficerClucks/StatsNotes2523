Here's an outline for your **README file** that includes all the details necessary to compile, execute the code, and a title page:

---

# **Operating Systems Project**

### Title: **Cooperating Processes using Shared Memory**

**Author**: Benjamin Cruickshank  
**Username**: cs020  
**Course**: Operating Systems  
**Instructor**: [Instructor's Name]  
**Date**: [Date of Submission]  

---

## **Project Overview**

This project demonstrates the creation of cooperating processes using shared memory in C. The program creates four child processes. Each child process performs a specific task of incrementing a shared variable (stored in shared memory) and prints its progress. The parent process waits for all child processes to finish before cleaning up the shared memory and terminating.

## **Files**

- **Project1.c**: The main C file containing the code for the project.
- **README.md**: This file, containing instructions on how to compile and run the program.
  
---

## **Compilation Instructions**

### Step-by-Step Guide to Compile the Program

1. **Ensure GCC is Installed**:
   Make sure you have GCC (GNU Compiler Collection) installed on your system. To verify, you can run:
   ```bash
   gcc --version
   ```
   If GCC is not installed, install it using the appropriate package manager for your operating system.

2. **Navigate to the Directory**:
   Open a terminal and navigate to the folder containing the `Project1.c` file.
   ```bash
   cd path/to/your/project/folder
   ```

3. **Compile the Code**:
   Use the following command to compile the C program:
   ```bash
   gcc -o Project1 Project1.c
   ```
   - The `-o Project1` specifies the output executable file name.
   - `Project1.c` is the C source file.

   If successful, this will create an executable file called `Project1`.

---

## **Execution Instructions**

### Step-by-Step Guide to Execute the Program

1. **Run the Executable**:
   After compiling the program, you can run the executable using:
   ```bash
   ./Project1
   ```

2. **Program Behavior**:
   - The program will create 4 child processes.
   - Each child process will increment the shared variable `total` by a specific number of times and print its results.
   - The parent process will wait for all child processes to complete, then it will detach and release the shared memory.
   - The parent will print a message each time a child process exits and display "End of program" after all processes are done.

---

## **Expected Output**

- Each child process prints the final value of `total` after completing its task.
- The parent prints the Process ID (PID) of each child as it exits.
- Example output:
   ```
   Process 1 total: 100000
   Process 2 total: 300000
   Process 3 total: 600000
   Process 4 total: 1000000
   Child with ID: 58452 has just exited.
   Child with ID: 58453 has just exited.
   Child with ID: 58454 has just exited.
   Child with ID: 58455 has just exited.
   End of program
   ```

---

## **Additional Notes**

- **Error Handling**: The program checks for errors during the creation of shared memory (`shmget`), attaching memory (`shmat`), and the process of forking.
- **Memory Management**: The shared memory is properly detached and deleted using `shmdt()` and `shmctl()`, respectively, to avoid memory leaks.
- **Process Coordination**: The parent process waits for all child processes to finish using `wait()` before detaching and releasing shared memory.

---

## **Troubleshooting**

- **Shared Memory Error**: If you encounter `shmget error` or `shmat error`, ensure that your system has sufficient shared memory resources available.
- **Fork Failure**: If the fork fails with "Fork failed", check your system's process limits using:
   ```bash
   ulimit -u
   ```

---

### **Conclusion**

This project demonstrates key concepts of process cooperation, shared memory, and synchronization using system calls in C. By following the instructions provided, you should be able to compile and run the program successfully.
