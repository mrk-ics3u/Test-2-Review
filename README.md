# Test 2 Review

Six practice exercises, built like the coding questions on the test. Each one
has its own file. Do them in any order.

| File | Practice |
|---|---|
| `1_motto_maker.py` | String methods |
| `2_box_calculator.py` | Math functions and string methods |
| `3_step_counter.py` | Lists of numbers |
| `4_playlist.py` | Lists of strings |
| `5_library_shelf.py` | Dictionaries |
| `6_points_table.py` | Dictionaries |

Leave the starter code in each file as it is. Write your code where the
comments tell you to.

## String and math methods

For Exercises 1 and 2, you may find some of these useful:

`abs()` · `.count()` · `.isalpha()` · `.isupper()` · `len()` · `math.ceil()` · `math.floor()` · `math.gcd()` · `math.hypot()` · `max()` · `pow()` · `.replace()` · `round()` · `.startswith()` · `.swapcase()`

Not all of them are needed.

## Exercise 1 - Motto Maker

The starter asks for a motto with the prompt `Enter a motto: `.

1. Print the motto with every `o` replaced by a zero (`0`).
2. Print the motto with its case swapped.
3. Print how many words are in the motto. Words are separated by one space.
4. If the motto starts with `We`, print `Team motto`. Otherwise print `Personal motto`.
5. Print the first 5 characters of the motto.

## Exercise 2 - Box Calculator

The starter asks for a label with the prompt `Enter a label: ` and a side length
with the prompt `Enter a side length: `.

1. The side length might be typed as a negative by mistake. Use its absolute value for every step below.
2. Print the area of the square (side to the power of 2), rounded to 2 decimals.
3. Print the length of the square's diagonal, rounded to 2 decimals. The diagonal is the hypotenuse of a right triangle whose two sides are both `side`.
4. Print the side rounded up to a whole number, then the side rounded down to a whole number.
5. If the label is all letters, print `Label OK`. Otherwise print `Letters only`.
6. If the first character of the label is uppercase, print `Capitalized`. Otherwise print `Not capitalized`.

## Exercise 3 - Step Counter

The starter has a while loop that asks `Steps: ` until `0` is entered.

1. Create an empty list above the loop. Inside the loop, add each number of steps to the list.
2. After the loop, print how many days were entered.
3. Print the first day's steps, then the last day's steps, using indexes.
4. Sort the list and print it.
5. Print `Lowest: ` and `Highest: ` followed by the lowest and highest steps, using indexes.
6. Use a loop to add up all the steps, then print `Total: ` followed by the total.

At least one day is always entered.

## Exercise 4 - Playlist

The starter has a while loop that asks `Add song: ` until `done` is entered.

1. Create an empty list above the loop. Inside the loop, add each song to the list.
2. After the loop, insert `Intro` at the start of the list, then print the list.
3. Ask `Skip song: `. If that song is in the list, remove it and print the list. Otherwise print `Song not found`.
4. Remove the last song in the list and print `Removed: ` followed by that song.
5. Print `Songs left: ` followed by how many songs are in the list.

## Exercise 5 - Library Shelf

The starter has a `books` dictionary (title: copies available) and a while loop
that asks `Borrow: ` until `done` is entered.

1. Add `Dune` with 2 copies, and delete `Hatchet` from the dictionary.
2. Inside the loop: if the title is in the dictionary and has more than 0 copies, take away 1 copy. If it has 0 copies, print `No copies left`. If the title is not in the dictionary, print `Not in library`.
3. After the loop, print each book as `title: copies` (example: `Holes: 1`).
4. Print `Copies available: ` followed by the total copies of all books.

## Exercise 6 - Points Table

The starter has a `points` dictionary (team: points) and a while loop that asks
`Winner: ` until `done` is entered.

1. Add `Gold` as a team with 0 points.
2. Inside the loop: if the team is in the dictionary, add 3 points to it. Otherwise print `Unknown team`.
3. After the loop, print each team as `team: points` (example: `Red: 6`).
4. Print `Top score: ` followed by the highest number of points.
5. If any team has 0 points, print `Some teams have no points`. Otherwise print `Every team has points`.

## Running your program

Open an exercise file and press the Run button in the top right corner of VS Code. Your output appears in the terminal at the bottom.

## Checking your work

Press **Ctrl+Shift+B** to test every exercise at once. Exercises you have not
started show `SKIP`. The others show one line per test:

```
PASS  1. Team motto, four words
FAIL  2. Personal motto, two words
```

When a test fails it shows what was expected and what your program printed. Fix your code and press Ctrl+Shift+B again.

## Reminders

- Prompts share a line with whatever prints next. The tests expect that, so don't add extra `print()` lines.
- Output is matched exactly, including capitals, spaces and punctuation.
- Every prompt ends with one space after the colon.
