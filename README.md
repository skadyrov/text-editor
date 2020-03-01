# Appboxo Android/IOS Take-Home Assignment

## Simple TextEditor app

<img src="/text-editor-sample.jpg" height="600">

#### 1. Helper toolbar to be shown just above the soft keyboard:
  - Tab: inserts tab character
  - Bullet points in the text editor (just '-' character)
  - If tab key (from helper toolbar) is pressed, indent the bullet point
  - If 'ENTER' key is pressed from soft keyboard, start the next line with the bullet point and same indentation

#### 4. Behavior of 'ENTER' key
  - If the current line starts with a bullet point, using 'ENTER' key should add a new line that has the same bullet point
  - If the current line has an indentation (tab characters), next line that will be added should have the same indentation
  
  You can represent the bullet point with '-' character.

**Note:** The above described functionalities are part of Evernote text editor: https://play.google.com/store/apps/details?id=com.evernote. Try to implement them to behave the same as in that text editor.

### We expect you to:
- Implement business rules and test the code base
- Use any code architecture you feel that suits the best (but also be prepared to justify your choice)
- Write in Kotlin (Android) / Swift (iOS)
