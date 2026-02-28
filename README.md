# pharma-care-cli

A small demonstration CLI command-line application that simulates a simple
pharmacy management system. Implemented in plain C, the program provides a
console-driven menu to manage medicines, suppliers, orders, and receipts —
making it useful as an educational demo or lightweight prototype.

**Features:**
- Inventory management: add, edit, delete, search, and list medicines.
- Supplier management: add, edit, remove, search, and list suppliers.
- Order and receipt creation with simple sales tracking.
- Admin panel with login, basic reporting, and contact/tech-team info.

## Quickstart

- Build with GCC (MinGW/Cygwin):

```
gcc -O2 -o pharma.exe main.c
```

- Build with Microsoft Visual C++ (Developer Command Prompt):

```
cl /Fe:pharma.exe main.c
```

- Run the program:

```
./pharma.exe
```

If the program accepts arguments, consult `main.c` for details.

## Files

- [main.c](main.c): C source — program entrypoint.
- [recieptDemo.txt](recieptDemo.txt): Example/demo output.
- [issues.txt](issues.txt): Notes and known issues.

## Contributing

If you want changes, open an issue in `issues.txt` or send a patch/PR with a short description.

