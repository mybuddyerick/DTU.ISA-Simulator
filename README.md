<div align="center">
  <img src="https://github.com/user-attachments/assets/9ea39d49-e732-4c1a-9bd7-f9d72f1e6d4d" alt="Logo" height="140">
</div>

<h1 align="center">02135 Introduction to Cyber Systems - ISA simulator Assignment</h1>

This is an implementation of an instruction-set architecture (or ISA) simulator in Python.  
Made by `Group 1`.  

⚠️ **Register 0 should always be 0** for this simulator to work!

Once the execution ends, the simulator prints the final state of the register file and the data memory to the console.  

### Test 1
This test verifies that all supported instructions are implemented and working correctly.  
Run with:  
```python3 isa-sim.py 10000 test_1/program_1.txt test_1/data_mem_1.txt```  

### Test 2 - Sorting Algorithm
This test sorts array of 10 values stored in the data memory starting from address 10.  
Run with:  
```python3 isa-sim.py 10000 test_2/program_2.txt test_2/data_mem_2.txt```  


### Test 3 - Collatz Conjecture  
This test simulates the Collatz sequence for a list of input numbers. It finds the number (Address: 254) that takes the most steps to reach 1 (Address: 255) and stores the result in memory.  
⚠️ **Do not use numbers equal or higher than 27**, it will overflow the simulator and results will not be accurate.  
Run with:  
```python3 isa-sim.py 10000 test_3/program_3.txt test_3/data_mem_3.txt```
