# AddOn Control Panel (ACP)
Stop logging out of the game just to change your AddOns!
ACP adds the "AddOns" button to the game's main menu (The one you get when you hit ESC). It allows you to manage your AddOns in game, with an interface which looks similar to the blizzard AddOn manager. ACP will help you deal with the "Clutter" that multi-part AddOns and libraries introduce by displaying your AddOns in logical arrangements. ACP has many features to make your AddOn list easy to manage, help you with missing libraries, and provide you with detailed information about each AddOn.

## Slash Commands
`/acp` - Show and Hide the ACP window
`/acp addset <set #>` - Enable an AddOn set
`/acp removeset <set #>` - Disable an AddOn set
`/acp Disableall` - Disable all AddOns (except protected and ACP)
`/acp default` - restore the Enabled AddOns to what was Enabled last time the UI was loaded

## Icon meaning
`Star`: Protected AddOn - this AddOn will not be Disabled when you choose Disable all, also if it is not Enabled when you log into the game, it will be re-Enabled and you will be prompted to reload the ui.
`Dk Grey Open Lock`: AddOn does not supply compatibility information
`Lt Grey Closed Lock`: AddOn has provided compatibility information

## AddOn compatibility
Helps you determine if the AddOn supports the current version of the game that you are running. You will see further information in the tooltip for the AddOn, and incompatible/out of date AddOns will be labeled in the main AddOn list.

## Credits
ACP is based on the work of 2 other projects rMCP, which is a version of MCP modified by Rophy, and MCP originally by Saien.

[![Build Status](https://travis-ci.org/sylvanaar/AddOn-control-panel.svg?branch=master)](https://travis-ci.org/sylvanaar/AddOn-control-panel)
