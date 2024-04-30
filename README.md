# What's this?

This is just a place for me to store my VSCode snippets, keyboard shortcuts and various other things

# Usage

Copy the Keyboard shortcuts over to the keyboard shortcuts JSON (found via the command pallette)

For the snippets, there's one for each language which coincides with what running the snippets command via the command pallette will open, where you can copy the data across.

# Keyboard Shortcuts:

### Deploy Source To Org

Mapped `CTRL + ALT + S` to deploy the currently viewed file to your Salesforce org. No different from right clicking it in the explorer view and clicking the deploy command

### Refresh Objects

Mapped `CTRL + ALT + R` to run the refresh objects command so the Apex Language Server has refreshed knowledge of fields etc (e.g intellisense)

# Snippets:

Not a comprehensive list here, but a vague list of the interesting ones. See the JSON directly to view the others.

### Finish Var
Command for it is `finishVar`, but there is a keyboard shortcut which is `CTRL + SHIFT + ENTER` which will use the current line and using RegEx, initialise it. It's using RegEx so still very primitive

![finishVarGif](/media/finishVar.gif)

### Flip comparison
Command for it is `invertNull`, but there is a keyboard shortcut which is `CTRL + SHIFT + SPACE` which will activate it on the hightlighted text
 
![flipComparisonGif](/media/flipComparison.gif)

### List To Loop / Loop To List
`listToLoop` or `loopToList`, it will use your clipboard as the source for the conversion. It's using RegEx so it's a very primitive conversion

![listToLoopAndLoopToListGif](/media/listToLoop-and-loopToList.gif)
