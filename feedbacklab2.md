# Feedback on Lab 2

## What is good
- Your Your turn code for Problems 1, 2 and 3 is correct: axis labels with units, the right 0.025 s edges, and the ninth reading appended with `np.append`.
- Problem 3: you predicted the median (77.35 K) as the bath temperature, which is the right choice.
- Problem 4: your predicted order, mode < median < mean, is correct.

## What to improve
1. The Drive cell stopped with "credential propagation was unsuccessful", and the rest of the notebook never ran: none of your answers has an output. When Colab asks for Drive access, choose the same Google account and allow it. Lab 2 does not save any files, so you can also skip that one cell and use Runtime → Run after on the next cell.
2. Problem 1: your prediction [2, 10, 14, 4] is close. The bins are half-open: [2.00, 2.05) includes 2.00 but not 2.05, and a reading of exactly 2.05 s goes into [2.05, 2.10). Count again with this rule.
3. Add one sentence to each Your turn that asks a question: Problem 1 (which bin is the tallest, and what does it tell you?) and Problem 3 (how many glitches can the median tolerate in nine readings?).
4. Problems 4 to 8: the Your turn cells, and the Predict cells of Problems 5 to 8, are still empty. Please try them; a partial answer is welcome.

I have not seen Lab 3 in your repository yet. Please push it when you can. If anything is unclear, write to me.

Prof. Dr. Bora Işıldak
