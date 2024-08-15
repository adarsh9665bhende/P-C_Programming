# Assign1-CS21BTECH11008

This folder contains the following files:

- **Assign1-Chunk-CS21BTECH11008.cpp**: Source code implementing the Chunk approach.
- **Assign1-Mixed-CS21BTECH11008.cpp**: Source code implementing the Mixed approach.
- **Assign1-Dynamic-CS21BTECH11008.cpp**: Source code implementing the Dynamic approach.
- **inp.txt**: Input file required for running the source files.
- **Assign1-report-CS21BTECH11008.pdf**: Report detailing the assignment.

## Instructions to Run

### Chunk Approach
1. Compile and run the Chunk approach:
   ```bash
   g++ -pthread -o chunk Assign1-Chunk-CS21BTECH11008.cpp
   ./chunk
### Mixed Approach
2. Compile and run the Mixed approach:
   ```bash
   g++ -pthread -o mixed Assign1-Mixed-CS21BTECH11008.cpp
   ./mixed
### Dynamic Approach
1. Compile and run the Dynamic approach:
   ```bash
   g++ -pthread -o dynamic Assign1-Dynamic-CS21BTECH11008.cpp
   ./dynamic


# Note
First line of inp.txt file should be N S K rowInc 
for all the source file
where N = matrix size,
S = Sparcity,
K = no of threads,
rowInc = row Increament