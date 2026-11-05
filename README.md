# QuestShare: bug reports and suggestions

This repository collects bug reports and suggestions for **QuestShare**, the party-questing addon for
WoW Forever. Download it on CurseForge: https://www.curseforge.com/wow/addons/questshare

There is no source code here; it is only the place to report problems.

## Report a bug

1. Check the [open issues](https://github.com/JohnChrin/QuestShare-issues/issues) first; if yours is
   there, add a comment or a 👍.
2. Otherwise open a [new bug report](https://github.com/JohnChrin/QuestShare-issues/issues/new/choose)
   and fill in the form. It asks for:
   - your QuestShare version (shown in the CurseForge app, or in the addon list on the character screen);
   - what you did, what you expected and what happened;
   - the output of `/qshare compat` (it lists the addons that get in QuestShare's way and every addon you
     have loaded);
   - a screenshot if something looks wrong, and any Lua error (BugSack or the game's error window).
3. If it is hard to reproduce, turn on the debug log with `/qshare debug on`, play until it happens,
   type `/reload`, and attach the file
   `World of Warcraft\_forever_\WTF\Account\<account>\SavedVariables\QuestShare.lua`.

A GitHub account is needed to open an issue. Without one, leave a comment on the CurseForge page.

## Suggest something

Use the [suggestion form](https://github.com/JohnChrin/QuestShare-issues/issues/new/choose). Say what you
were trying to do in game, not only the change you want.
