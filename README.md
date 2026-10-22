# Fix my code

Jumping into an existing code base and fixing it, without recoding everything.

## Tasks

| # | File | Bug | Fix |
|---|------|-----|-----|
| 0 | `0-fizzbuzz.py` | `15` printed `Fizz`: the `% 3` check ran before the `% 3 and % 5` check | Test the FizzBuzz case first |
| 1 | `1-print_square.js` | Size parsed in base 16 (`10` became 16) | `parseInt(..., 10)` |
| 2 | `2-sort.rb` | Insertion at `i - 1` put each number one slot too early | `result.insert(i, i_arg)` |
| 3 | `3-user.py` | Stored hash is lowercase, comparison used `.upper()` | Compare with `.lower()` |
| 4 | `4-delete_dnodeint/` | Middle delete updated `prev->prev` instead of `prev->next`, and read the node after `free` | Relink `prev->next` / `next->prev`, then `free` |

## Author

Antonio Torres
