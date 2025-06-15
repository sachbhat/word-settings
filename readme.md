

## What It Contains
- Custom keyboard shortcuts
- AutoCorrect entries
- Custom styles
- Toolbar/ribbon customizations
- Macros
- Default formatting settings

## Where It Lives:
Usually something like:
`~/Library/Application Support/Microsoft/Office/User Templates/`
or
`~/Library/Group Containers/UBF8T346G9.Office/User Content/Templates/`

## Apply to Other Computers:
Replace the `Normal.dotm` file on other machines and your shortcuts should transfer.
This is the main file that contains your Word customizations!

```
bash# Find it
find ~/Library -name "Normal.dotm" 2>/dev/null

# Copy to your git repo
cp [path-to-normal.dotm] ./word-settings/
```