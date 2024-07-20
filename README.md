* 🌙 Dark (000) and vibrant theme 

For for *Monokai Vibrant* 

- What is different 
  1. Complete dark mode. Background color is #000
  2. Higher contrast on what tab is being used 
  3. Higher contrast when a tab is not saved. 


## Install

1. Open the **Extensions** sidebar in VS Code.
2. Search for `Monokai #000`.
3. Click the **Install** button
4. Go to Preferences ‣ Color Theme ‣ **Monokai Vibrant**

## Disable Italics

If you are not using a font that does not support italics, you can add this to your `settings.json` to disabled them.

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "Monokai Vibrant - No Italics",
      "scope": [
        "comment",
        "string.comment",
        "variable.language",
        "keyword",
        "storage",
        "variable.parameter"
      ],
      "settings": {
        "fontStyle": ""
      }
    }
  ]
}
```
