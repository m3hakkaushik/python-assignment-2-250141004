# GradeBook ANALYSER

Hey! This is a little Python thingy that helps you keep track of student marks and grades. You can type stuff in or load it from a file. It’s pretty chill.

## What’s This Do?

- You can write student names and their marks yourself.
- Or load all the marks from a CSV file (like a list in a file).
- It tells you the average mark, middle mark, top mark, and lowest mark.
- It gives each student a grade letter (A, B, C, D, or F).
- It counts how many people got each grade.
- It tells you who passed and who flunked.
- It prints a report card with all the info.

## How To Use It

1. Run the `gradebook.py` thing.
2. You’ll see a menu with these numbers:
   - Press `1` if you wanna type names and marks.
   - Press `2` if you wanna load marks from a file.
   - Press `3` if you wanna quit (bye!).
3. If you pick 1, just type in the name and marks for each student. When done, type `done`.
4. If you pick 2, it’ll ask for the file name. Give it, like, `student_marks.csv`.
5. After loading or typing, it shows you all the scores and grades.
6. Hit ENTER to go back to the menu if you want.

## What’s The File Look Like?

If you use a CSV file, it’s like a list with two things: name and mark. No fancy headers, just plain stuff:

Kirti,78
Palak,92
Ridhima,54
Aishu,81
Agrima,39
Ronak,66
Tani,99

## What You’ll See

Once loaded, it shows:

- The class average mark.
- The middle score.
- Highest and lowest marks.
- How many folks got A, B, C, D, or F.
- Who passed and who didn’t.
- A neat little report card.

## What You Need

- Python 3 (duh).
- No fancy libraries, just what’s built-in.

## Example Run

Average: 72.71
Median: 78
Top Score: 99
Lowest Score: 39

Grades Breakdown:
A - 2 folks
B - 1 person
C - 1 person
D - 1 person
F - 2 people

Passed (6): Kirti, Palak, Ridhima, Aishu, Ronak, Tani
Failed (1): Agrima

--- Report Card ---
Name Marks Grade
Kirti 78 C
Palak 92 A
Ridhima 54 F
Aishu 81 B
Agrima 39 F
Ronak 66 D
Tani 99 A

