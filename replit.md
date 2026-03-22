# C Data Structures Lab

## Project Overview
An educational C programming laboratory for practicing Abstract Data Types (ADTs) — specifically Lists and Stacks. Students implement functions in `exercises.c` to pass a set of automated tests.

## Technology Stack
- **Language**: C (compiled with `gcc -g -Wall -Werror`)
- **Build**: Custom shell script (`test.sh`)
- **No frontend** — purely command-line

## Project Structure
- `exercises.c` — The only file students should modify. Contains 5 exercises to implement.
- `arraylist.c` / `arraylist.h` — List ADT implementation.
- `stack.h` — Stack ADT (header-only wrapper around List ADT).
- `test.c` — Test suite with `main`. Compiled together with `exercises.c`.
- `test.sh` — Script that compiles, runs tests, logs results, and optionally pushes to GitHub.
- `log` — Auto-generated log file tracking compilation and test scores over time.

## Exercises
1. `crea_lista()` — Create a list and add integers 1–10.
2. `sumaLista(List *L)` — Return the sum of all elements.
3. `eliminaElementos(List *L, int elem)` — Remove all elements equal to `elem`.
4. `copia_pila(Stack *P1, Stack *P2)` — Copy P1 into P2 preserving order.
5. `parentesisBalanceados(char *cadena)` — Check if parentheses are balanced.

## Workflow
- **Run Tests** (`bash test.sh`) — Compiles and runs all tests, shows scores, optionally pushes progress to GitHub.

## Scoring
Total: 70 points across 5 exercises (0/10, 0/10, 0/20, 0/10, 0/20 by default on fresh clone).
