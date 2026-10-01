# PLP Python Week 7: Shopping List Manager

## File Descriptions
- **list_warmup.py**: Demonstrates basic list operations including index access, appending items, removing items, and checking length.
- **shopping_list.py**: An interactive command-line shopping list manager supporting add, remove (with safety checks), show, and exit operations.
- **list_report.py**: Generates a formatted report from a preset list, displaying numbered items, counting names longer than 4 letters, and finding the longest item name.

## Why is it safer to check in before calling .remove()?
Checking if an item exists in a list using the `in` keyword before calling `.remove()` prevents the program from throwing a `ValueError` exception and crashing. If you attempt to remove an item that isn't present without this validation, Python halts execution immediately.
