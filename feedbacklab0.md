# Feedback on Lab 0

## What is good
- Problem 1: both numbers, 4.936 s and 2.006 s, and the right reason in the Your turn (`L` was in memory, and the restart clears it).
- Problem 6: you saw that pandas skips `NaN` while NumPy returns `nan`, and your formula `T.std()/np.sqrt(T.count())` gives the right 0.816 °C.

## What to improve
1. Run the notebook from the top. Two given cells show a `NameError` (`t` and `np` not defined), which happens when cells are run out of order. Use "Runtime → Restart session and run all".
2. Predict cells must be valid Python. `prediction = yes, [-1, -3, -5]` (Problem 4), `prediction = no they do not follow` (Problem 7) and the text in Problems 5 and 6 stop the notebook. Put text in quotes, for example `prediction = "yes, [-1, -3, -5]"`.
3. Problem 3: the Predict cell is code (`np.diff(x)/0.111`), not a number. Write the number you expect the student's method to give, with one sentence of reason.
4. Problems 4, 5 and 6 (Your turn): your answers are written as comments, so they never run. Remove the `#`. In Problem 5 use `print(R)`; `print(R=" ")` would raise a TypeError.
5. Problems 2, 7 and 8 (Your turn) and the Problem 8 Predict cell are empty. A partial answer is welcome.

If anything is unclear, write to me.

Prof. Dr. Bora Işıldak
