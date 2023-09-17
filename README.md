# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create Codeblocks in markdown you need to use three backticks (`). 
- Not to be confused with quotation (').

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")
```

- When you can you should attempt to apply syntax highlighting to Codeblocks.

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")
```

<img width="200px" src="https://github.com/netcode-daniel/github-docs-example/assets/12187128/717f0727-515b-4885-95fa-f063fa52578c" />

Good Cloud Engineers use Codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  File "example.py", line 2, in <module>
    print(undefined_variable)
NameError: name 'undefined_variable' is not defined
```
> Here is an example of using a codeblock for an error that appears in bash.


On both macOS and Windows, you can take screenshots using hotkeys or keyboard shortcuts. Here's how you can do it on both operating systems:

![Screenshot-Example](https://github.com/netcode-daniel/github-docs-example/assets/12187128/258607fc-7d03-4e0f-85da-2b54ef7adf1d)


**macOS:**

1. **Capture Entire Screen:**
   - To capture the entire screen, press `Command (⌘) + Shift + 3` simultaneously.
   - The screenshot will be saved as a file on your desktop by default.

2. **Capture a Selected Portion of the Screen:**
   - To capture a selected portion of the screen, press `Command (⌘) + Shift + 4`.
   - Drag to select the area you want to capture.
   - Release the mouse button to take the screenshot.
   - The screenshot will be saved as a file on your desktop.

3. **Capture a Specific Window:**
   - To capture a specific window, press `Command (⌘) + Shift + 4`, then press the `Spacebar`.
   - Click on the window you want to capture.
   - The screenshot of the selected window will be saved as a file on your desktop.

**Windows:**

1. **Capture Entire Screen:**
   - To capture the entire screen, press `PrtScn` (Print Screen) key.
   - The screenshot will be copied to your clipboard. You can paste it into an image editing program like Paint or directly into a document.

2. **Capture the Active Window:**
   - To capture only the currently active window, press `Alt + PrtScn`.
   - The screenshot of the active window will be copied to your clipboard.

3. **Capture a Selected Portion of the Screen (Windows 10 and later):**
   - To capture a selected portion of the screen, press `Windows + Shift + S`. This will open the Snip & Sketch tool, allowing you to select the area you want to capture.
   - The screenshot will be copied to your clipboard, and you can paste it into an image editing program or document.

4. **Capture a Selected Portion of the Screen (Windows 7 and earlier):**
   - Windows 7 and earlier versions do not have a built-in hotkey for capturing a selected portion of the screen. You can use third-party tools like "Snipping Tool" or "Snip & Sketch" (available on Windows 10 and later) for this purpose.

Remember that the exact hotkeys and features may vary slightly depending on your macOS or Windows version, but the methods listed above are generally applicable to most versions.


## Step 3 - Use Github Markdown Flavored Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3
- [ ] Finish Step 4
- [ ] Finish Step 5

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with Lightnng | `:cloud_with_lightning:` | 🌩️ |

## Step 5 - How to create a table 

You can use the following markdown format to create tables: 

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with Lightnng | `:cloud_with_lightning:` | 🌩️ |
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

## External References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/#introduction) 
- [Get started with GitHub documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#relative-links) 
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>



