
--- question ---

---
legend: Question 2 of 3
---

A code club member has written the code below to display a message one letter at a time. They can't understand why it is only displaying the last letter on their LED matrix. 

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 23
line_highlights: 
---
sense.show_letter("H", red, blue)
sense.show_letter("e", orange, indigo)
sense.show_letter("l", yellow, green)
sense.show_letter("l", green, yellow)
sense.show_letter("o", blue, red)
--- /code ---

![A screenshot of the error. An O is displayed on the SenseHAT.](images/q2.PNG){:width="300px"}

Which code snippet is missing from their code?

--- choices ---

- (x) `sleep(1)`

  --- feedback ---

Correct! In order for you to be able to see each letter, you need to create a pause in the code. The sleep will pause the code for 1 second. 

  --- /feedback ---

- ( ) `wait(1)`

  --- feedback ---

Not quite, you **do** need the code to wait for 1 second but this isn't the right code snippet to use. 

  --- /feedback ---

- ( ) `sleep()`

  --- feedback ---

Almost! This is the correct code snippet to use but you need to specify how many seconds to sleep for within the brackets. 

  --- /feedback ---

--- /choices ---

--- /question ---
