# botboiler-helpers README

A Visual Studio Code extension to provide snippets to assist when developing bots using the [BotBoiler](https://github.com/MSFTAuDX/BotBoiler) sample code. You'll need this codebase up before this extension will be of any use. 

Consider using the [```botboiler```](https://www.npmjs.com/package/generator-botboiler) Yeoman generator and make sure you head to the main [BotBoiler](https://github.com/MSFTAuDX/BotBoiler) for usage and samples.

## Usage

From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (macOS) select snippts. Start typing ```bb``` and you'll see the snippets. 

Once the snippet is in, press tab to navigate the editable template fields. 

<img src="https://user-images.githubusercontent.com/5225782/28900787-16062738-7837-11e7-9d47-c652c90944b6.gif" width="720"/>

## Shortcuts

We recommend adding a shortcut to snippets. In your keyboard bindings file add the following:

```json
{
    "key": "ctrl-alt-k",
    "command": "editor.action.insertSnippet"
}
```

## Installation

1. Install Visual Studio Code 1.11.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (macOS)
4. Select `Install Extension`
5. Choose the extension (botboiler-helpers)
6. Reload Visual Studio Code