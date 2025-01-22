# Obsidian--ITS-CheckBoxes
Modified Obsidian--ITS--Theme css files for checkboxes. This will also bring over the whole theme of ITS-Theme options. I did not strip that code out yet to make a lightweight version if people do not want the whole theme. I will also be submitting a pull request of the original code base with these changes. Unsure how long that will take if it does at all.

# Original code can be found here [S1Rvb--ITS-Theme](https://github.com/SlRvb/Obsidian--ITS-Theme)

# Changes
- Added the functionality to be able to select each checkbox style independant of the others for strikethrough or not.
- Changed the strikethrough color for `--chbx-d` - line 7850 & 7868 to `255,50,0` to allow a red strikethrough on the "Dropped" checkbox item.

# Plugins required to alter checkbox strikethrough
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)

# Using the .css file
> - To utilize the .css file you can download it or just copy all the text from the .css file and make a new <FILENAME>.css and put it in there on your computer.
> - Once you have the new file put it in the `<YOUR VAULT FILEPATH>\.obsidian\snippets\` folder.
> - Once in there you should be able to go in your Obsidian vault using the app. Then go to the settings (cog wheel lower right of the left pane, next to your vault selection) - "Options" > "Appearances" > Scroll all the way down and you should see the <FILENAME>.css, whatever you decided to name it.
> - Check the box next to it.

# Adjusting the strikethrough (Requires the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin.
> - Go to the settings (cog wheel lower right of the left pane, next to your vault selection) - Scrool down on the left side to "Communinty Plugins" > "Style Settings" > "ITS Theme Settings".
> - Here you can either use the search bar at the top with the keyword "strikethrough" or use the drop down of the "ITS Theme Settings" > "Note" > "Checkboxes".
> - The "Restore Checkbox Strike" will turn on ALL the strikethroughs for checkboxes except `[ ] ` or "Unchecked".
> - The "Advanced Checkbox Strike" is supposed to be an option open the dropdown for all the checkboxes, didnt get it working yet.
> - The other are self-explanatory.

# What the checkboxes look like
> - Information on what the checkboxes look like when checked can be found on the original coders site on [Obsidian](https://publish.obsidian.md/slrvb-docs/ITS+Theme/ITS+Theme).

# TO-DO:
- Strip the code out and getting it working without using the theme.
- Do a pull request to get the functionality into the main code base (if they wish to add it)
- Publish to Obsidian.
