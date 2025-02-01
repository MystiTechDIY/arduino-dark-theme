# Arduino Dark Theme for VS Code

## To make the code appear exactly like it does on Arduino, add the following commands to your settings.json file:

  `"C_Cpp.enhancedColorization": "disabled"`

  `"editor.bracketPairColorization.enabled": false`

## How to do it?

1. Press the shortcut Ctrl + Shift + P
2. Search for: Open User Settings (JSON)
3. Press enter and edit the file

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

### Screenshots:
![screenshot2](https://github.com/user-attachments/assets/f3b0fe11-80f8-4b39-8896-cc540ad82301)

![arduino vs code](https://github.com/user-attachments/assets/2365db53-2ef0-4c85-b75c-53f78cec6f99)

