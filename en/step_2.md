## Create a palette

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step, you will set up your SenseHAT and create a colour palette for your rainbow message. 
</div>
<div>
![A screenshot of what will be achieved by the end of this step.](images/step_two_output.PNG){:width="300px"}
</div>
</div>

--- task ---

Open the [rainbow message starter project](https://trinket.io/html/bcf1978d5a){:target="_blank"}.

--- /task ---

### Set up the SenseHAT

The SenseHAT uses a **library** of code that needs to be imported into your program. 

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Libraries**</span> are code blocks that have been made to perform a group of tasks for a particular purpose. They allow programmers to share common programming solutions. The SenseHAT library has modules of code that allow programmers to interact with the sensors and the LED matrix on the SenseHAT.
</p>

--- task ---

On line 3, enter the code `from sense_hat import SenseHat`. This will import the code from the `sense_hat` library.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 3
---
# Import the libraries

from sense_hat import SenseHat

# Set up the SenseHAT

--- /code ---

--- /task ---

--- task ---

On line 7, enter the code `sense = SenseHat()`. This will set up your SenseHat.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 7
---
# Import the libraries

from sense_hat import SenseHat

# Set up the SenseHAT

sense = SenseHat()

# Rainbow colours
--- /code ---

--- /task ---

--- task ---

**Test** your code by clicking on **Run**. You should see the SenseHAT emulator on the right hand side. 

![A screenshot of the SenseHAT emulator in Trinket.](images/setup-sensehat.PNG){:width="300px"}

**Tip**: If you are using a physical SenseHAT then this step isn't needed. 

--- /task ---

### Set up your colour palette



