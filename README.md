# CL1 Practical — Final Year (7th Sem) — All Codes

Repository purpose
- Centralized collection of CL1 practical programs and lab solutions for 7th semester.
- Each folder contains source code, sample input/output, and a short README where needed.

Structure (recommended)
- /exp01/ — Experiment 1
    - src/ — source files (e.g., exp01.c, exp01.cpp, Exp01.java, script.py)
    - input.txt — sample input
    - output.txt — expected output
    - README.md — brief notes for this experiment
- /exp02/
- ...
- /common/ — helper scripts, Makefile, utils
- README.md — this file

Naming conventions
- Use lowercase, hyphen-separated names: exp-01-prime.c, exp-02-socket-server.cpp
- Put language extension that matches the source language.

How to build and run (examples)
- C (gcc)
    - Build: gcc -Wall -O2 -o exp01 src/exp01.c
    - Run: ./exp01 < input.txt
- C++ (g++)
    - Build: g++ -std=c++17 -Wall -O2 -o exp02 src/exp02.cpp
    - Run: ./exp02 < input.txt
- Java
    - Build: javac src/Exp03.java
    - Run: java -cp src Exp03 < input.txt
- Python
    - Run: python3 src/exp04.py < input.txt
- Makefile
    - Use `make` to build selected experiments if provided.

How to add a new experiment
1. Create folder expNN (NN = two-digit number).
2. Add src/, input.txt, output.txt, and README.md.
3. Update top-level README.md with a one-line description and filename(s).
4. Commit with a descriptive message:
     - git add .
     - git commit -m "Add exp05: matrix multiplication (C++)"

Documentation tips for each experiment
- Objective: one-line goal
- Algorithm: brief steps / complexity
- Usage: build/run examples
- Sample I/O: include small sample input and expected output
- References: any book or online reference (optional)

Testing and grading checklist
- Code compiles without warnings (use -Wall)
- Handles edge cases and invalid input gracefully
- Includes comments and readable variable names
- Matches sample output format exactly

License & attribution
- Add a LICENSE file if you want to share (MIT or BSD recommended for public repos).
- If code is taken from external sources, cite them in the experiment README.

Contact / Maintainer
- Maintainer: (Your Name or Student ID)
- Email: your.email@example.edu

Quick starter README entry example
- exp01 — basic file I/O in C
    - src/exp01.c — read integers and print their sum
    - Build: gcc -o exp01 src/exp01.c
    - Run: ./exp01 < input.txt

Use this template to organize all CL1 practical codes. Update experiment folders with code and brief READMEs for easy navigation and grading.