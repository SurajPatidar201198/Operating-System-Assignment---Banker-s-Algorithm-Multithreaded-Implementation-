# Operating System Assignment-Bankers Algorithm Multithreaded Implementation
## Bankers Algorithm

### Question

Write a multithreaded program that implements the banker's algorithm. Create n threads that request and release resources from the bank. The banker will grant the request only if it leaves the system in a safe state. It is important that shared data be safe from concurrent access. To ensure safe access to shared data, you can use mutex locks.

### Solution
    
   - [Multithreaded Implementation in C](./bankers_algorithm.c)
   
### Compiling Instruction
```bash
# compile
gcc bankers_algorithm.c -std=c99 -pthread -o bankers_algorithm

# execute
./bankers_algorithm
```



