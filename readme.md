

## What It Contains
- Custom keyboard shortcuts
    - Cmd+1 => H1
    - Cmd+2 => H2
    - Cmd+3 => H3
    - Cmd+4 => H4
    - Cmd+Opt+Shift+> => Quote
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

``` bash

# Find it
find ~/Library -name "Normal.dotm" 2>/dev/null

# Copy to your git repo
cp [path-to-normal.dotm] ./word-settings/
```