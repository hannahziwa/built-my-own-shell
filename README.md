# Mini Python Shell

A lightweight, educational command-line shell written in Python.

This project is a **simplified re-implementation of a Unix-like shell**, built to explore how shells work under the hood: command parsing, built-ins, pipelines, history, and tab completion. It’s not meant to replace your terminal, it’s meant to help you understand it.

---

## What This Shell Can Do

### Built-in Commands
The shell includes several core built-ins that behave similarly to their Unix counterparts:

- `echo` – print text  
- `pwd` – show the current directory  
- `cd` – change directories  
- `type` – tell you whether a command is built-in or where it lives  
- `exit 0` – exit the shell  
- `history [n]` – show command history (optionally limited)

---

### External Commands
Any executable found in your system’s `PATH` can be run, just like in a normal shell:

```bash
ls
grep foo file.txt
cat file.txt
