# ⭐ Arduino-Inspired Dark Theme for Visual Studio Code

### A theme for Arduino Dark enthusiasts who can't let go of its classic colors.

## 📌 Changing the Default User Settings in VS Code

### To replicate the Arduino IDE Dark Theme exactly, modify your settings.json file with the following settings:

  `"C_Cpp.enhancedColorization": "disabled"` – Disables enhanced syntax highlighting, keeping the default theme colors.

  `"editor.bracketPairColorization.enabled": false` – Disables bracket pair colorization, ensuring that all brackets remain a single default color.

### To modify the settings:
1. Open the command palette by pressing Ctrl + Shift + P.
2. Search for: Open User Settings (JSON).
3. Press Enter to open the settings file.
4. Edit the file and save your changes.
5. After saving, the new settings should be automatically loaded.

### The full file (settings.json) should look something like this:
```json
{
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "editor.defaultFormatter": "ms-vscode.cpptools",
  "editor.formatOnSave": true,
  "files.autoSave": "afterDelay",
  "explorer.confirmDelete": true,
  "explorer.confirmDragAndDrop": false,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "workbench.colorTheme": "Arduino Dark Theme ",
  "C_Cpp.enhancedColorization": "disabled",
  "editor.bracketPairColorization.enabled": false
}
 ```

## 📌 Changing the Default Formatting in VS Code  

### 1. Add a `.clang-format` file.
Create a new file named `.clang-format` in the root directory of your project. This file defines the formatting rules for your C/C++ code.

### 2. Add the following configuration and save the file:  
```yaml
BasedOnStyle: Google
AllowShortIfStatementsOnASingleLine: AllIfsAndElse
PointerAlignment: Left
DerivePointerAlignment: false
ColumnLimit: 120
 ```
### Explanation of the settings:

`BasedOnStyle: Google` – Uses Google's default formatting as a base, which includes 2-space indentation and other common conventions.

`AllowShortIfStatementsOnASingleLine: AllIfsAndElse` – Allows short if statements and if-else blocks to stay on a single line. 

`PointerAlignment: Left` – Formats pointers as `char* ptr` instead of `char *ptr`.

`DerivePointerAlignment: false` – Ensures that pointer alignment is explicitly set by PointerAlignment.

`ColumnLimit: 120` – Sets the maximum line length. Default is 80 characters, but 120 allows for longer lines.

## 🖼️ Screenshots:

![theme_screen1](https://github.com/user-attachments/assets/91a7f030-9d1c-463f-8787-a69491d4d613)

![theme_screen2](https://github.com/user-attachments/assets/5eeed7d0-edee-4eb8-bbbf-a2f44039715d)
