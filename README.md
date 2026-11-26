# CS101 Python Basics

Foundational Python programs, tracked with Git.

## Files
| File | What it shows |
|------|---------------|
| hello.py | Printing output |
| type_casting.py | int, float, str, bool conversion |
| operators.py | Arithmetic, comparison, logical operators |

## Run
    python hello.py

## Branches
- `main`: stable code
- `feature/type-casting`
- `feature/operators`
- `feature/greeting`: used for the merge conflict

## Merge conflict
`main` and `feature/greeting` both changed the line in `hello.py`.
Git stopped the merge. I resolved it by combining both messages,
removing the conflict markers, then committing the result.

## View history
    git log --oneline --graph --all
