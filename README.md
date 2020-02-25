# Appboxo Android/IOS Take-Home Assignment

## Simple TextEditor app

<img src="/text-editor-sample.jpg" height="600">

#### 1. Helper toolbar to be shown just above the soft keyboard:
  - Tab: inserts tab character
  - Check mark: Adds an empty check mark
  - Styling buttons:
    - Bold: Converts selected text into bold style. If no text was selected, new text entered from now on should be all in bold.
    - Italic: Converts selected text into italic style. If no text was selected, new text entered from now on should be all in italic.
    - Highlighter (use yellow as highlight color)
    - All three above styling buttons should be combinable, i.e. if italic is used on an already bold text, it should convert to italic & bold text

#### 2. Check marks in the text editor
  - Convert [] or [x] into a check mark
  - Clicking on the check mark should mark it checked or empty (based on its existing state).

#### 3. Bullet points in the text editor
  - If inserted on an empty line, convert that line into a bullet points
  - If there was a line in that text, convert that text into a bullet point and move cursor to the end of the line
  - If tab key (from helper toolbar) is pressed, indent the bullet point
  - If 'Enter' key is pressed from soft keyboard, start the next line with the bullet point and same indentation

#### 4. Behavior of 'ENTER' key
  - If the current line starts with a bullet point, using 'ENTER' key should add a new line that has the same bullet point
  - If the current line has an indentation (tab characters), next line that will be added should have the same indentation

**Note:** The above described functionalities are part of Evernote text editor: https://play.google.com/store/apps/details?id=com.evernote. Try to implement them to behave the same as in that text editor.

### We expect you to:
- Implement business rules and test the code base
- Use any code architecture you feel that suits the best (but also be prepared to justify your choice)
- Write in Kotlin (Android) / Swift (iOS)
