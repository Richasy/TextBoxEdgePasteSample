# TextBoxEdgePasteSample

**Csae link:** https://docs.microsoft.com/en-us/answers/questions/131840/uwp-textbox-does-not-accept-any-key-inputs-after-a.html

**Reproduced Environment**: Windows 10 Build 2004.   VS 2019

**Reproduced Steps:**

1.	Download sample and run.
2.	Make sure there is only this one application on the desktop, or no other application covering the sample application
3.	Copy a piece of text, and then when the sample application window loses focus, move the cursor to the right edge of TextBox2 (make the vertical line of the "I" cursor coincide with the right border line of the TextBox), then right click and select Paste. At this time, TextBox2 will focus, but no more characters can be entered until it is refocused.
4.	The conditions for reproducing this problem are relatively harsh. You can try to switch between the two TextBoxes.

