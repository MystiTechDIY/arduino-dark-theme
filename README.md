# Arduino-Inspired Dark Theme for Visual Studio Code

### A theme for Arduino Dark enthusiasts who can't let go of its classic colors.

### To replicate the Arduino IDE Dark Theme exactly, modify your settings.json file with the following settings:

  `"C_Cpp.enhancedColorization": "disabled"` – Disables enhanced syntax highlighting, keeping the default theme colors.

  `"editor.bracketPairColorization.enabled": false` – Disables bracket pair colorization, ensuring that all brackets remain a single default color.

## To modify the settings:
1. Open the command palette by pressing Ctrl + Shift + P.
2. Search for: Open User Settings (JSON).
3. Press Enter to open the settings file.
4. Edit the file and save your changes.
5. After saving, the new settings should be automatically loaded.

### The full file (settings.json) should look something like this:
```json
{
  "editor.formatOnSave": true,
  "files.autoSave": "afterDelay",
  "[cpp]": {
    "editor.defaultFormatter": "ms-vscode.cpptools"
  },
  "editor.defaultFormatter": "ms-vscode.cpptools",
  "explorer.confirmDelete": true,
  "explorer.confirmDragAndDrop": false,
  "git.enableSmartCommit": true,
  "clang-format.fallbackStyle": "Google",
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "workbench.colorTheme": "Arduino Dark Theme ",
  "C_Cpp.clang_format_style": "file",
  "C_Cpp.clang_format_fallbackStyle": "Google",
  "C_Cpp.enhancedColorization": "disabled",
  "editor.bracketPairColorization.enabled": false,
  "git.confirmSync": false,
}
 ```

## Screenshots:

![theme_screen1](https://github.com/user-attachments/assets/91a7f030-9d1c-463f-8787-a69491d4d613)

![theme_screen2](https://github.com/user-attachments/assets/5eeed7d0-edee-4eb8-bbbf-a2f44039715d)
