RetroArch-Run-Ahead-Overrides

These are Run-Ahead By Game Overrides for RetroArch

The aim with this project is to fully take advantage of the Run-Ahead feature in RetroArch and have a result of the lowest input lag possible with this feature.

All Games will use the lowest frame delay action for the basis of it's Run-Ahead Frames.

What this means is that if for example when hitting the A Button in a game the frames before this action shows on the screen is 3 Frames but when hitting the B Button in the same game the frames before this action shows on the screen is 2 Frames, we will set the run_ahead_frames = "2".

All Presets Default to having the following settings

run_ahead_enabled = "true"
run_ahead_secondary_instance = "true"

Note:
Run-Ahead Secondary Instance may cause performance issues on certain systems so toggle off if needed. The reason behind keeping the run_ahead_secondary_instance = true is because with out it set it can cause audio issues.

To use these files please place the folders provided in the following RetroArch Directory

/config/

example: /config/Snes9x/

If you do not have the override directory you will have to make one to match the core first

Override Files for Cores Currently Provided:
Snes9x

Configuration Files Should work for any core however you will need to name the folder appropriately

ROM Names must match the .CFG file Names

CFG Files as downloaded have names based on the No-Intro Romset

All Frame Settings Are Logged Here: https://docs.google.com/spreadsheets/d/1ql9OYGWW7fXbR76VijqsfqPoX7DFFtQkIIKtK7xePHc/edit#gid=0

Please feel free to update the file if you find any inconsistencies.
