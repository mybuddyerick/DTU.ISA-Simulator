# ISA-simulator
This is an implementation of an instruction-set architecture (or ISA) simulator in Python.  
Made by `Group 1`.  

**Test 1** is a simple test where all instructions are used. In order to run it, use the command:  
```python3 isa-sim.py 10000 test_1/program_1.txt test_1/data_mem_1.txt```  

**Test 2** orders an array of 10 values stored in the data memory starting from address 10. In order to run it, use the command:  
```python3 isa-sim.py 10000 test_2/program_2.txt test_2/data_mem_2.txt```  


**Test 3** is a Collatz Conjecture simulator, where a list is provided in the `data_mem_3.txt` and it finds the number that takes the most steps to reach one. **Do not use numbers higher than 27** since it will overflow and results will not be accurate. To run test 3, use the command:  
```python3 isa-sim.py 10000 test_3/program_3.txt test_3/data_mem_3.txt```