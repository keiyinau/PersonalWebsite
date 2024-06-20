# How to make a spam bot using python
## Requirement
1. Understand basic for loop and how to read files using python

2. Installed pyautogui and pyperclip

## Example Code

``` python
import pyautogui
import pyperclip
import time
f='spamming.txt'
print("10 second focus on the window")
l=[]
a=[]

time.sleep(4)
with open(f,"r",encoding="utf-8") as file:
    for j in file:
        l.append(j)
    a=[j.split("\n")[0] for j in l]
    print(a)
    for i in a:
        pyperclip.waitForPaste()
        #Some copy Command
        
        pyperclip.copy(i)
        
        print(i)
        #some paste command
        pyautogui.hotkey('ctrl', 'v')
        pyautogui.press('enter') 
        time.sleep(1.5)
```