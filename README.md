# DSA-
# CPU Process Scheduling and Prime Number Calculation

## Approach
1. **Simple Process Scheduling Algorithm**:
   - Implemented a circular linked list to represent processes.
   - Each process is scheduled to receive CPU time in cycles, with the ability to add new processes dynamically.
   - The state of processes is displayed after each cycle.

2. **Very Large Prime Number Calculation**:
   - Used a linked list to store a 1024-bit random number in segments of 64 bits.
   - Implemented a simple trial division method to check for primality across multiple nodes in the linked list.

## Assumptions
- Each node in the circular linked list for process scheduling contains a unique process ID and execution time.
- The random number for prime checking can be constructed from segments appended to the linked list.
- 
## Challenges Faced
- Managing the circular nature of the linked list while ensuring correct removal and addition of processes.
- Implementing a primality test that correctly handles a large number stored in a linked list.

# CPU Process Scheduling
-![image](https://github.com/user-attachments/assets/bcbb5a9c-b1e2-4f23-a067-a3f249f65487)
# Prime Number Calculation
-![image](https://github.com/user-attachments/assets/5f54d515-7cbf-4ec9-98fe-173d893ea521)

