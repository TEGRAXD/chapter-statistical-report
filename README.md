# Chapter Statistical Report
Chapter Statistical Report is a SourceMod plugin that *obviously* written in SourcePawn. This allow players to get information of their basic statistic such as CI & SI kills, headshot kills, and headshot accuracy. This plugin work best in Coop mode.

## Console Variable (ConVar)
- csr_version
- csr_headshot_accuracy_compare (default: 1)
- csr_ignore_bots_kills (default: 0)
- csr_only_human_player (default: 0)
- csr_print_mode (default: 0)
- csr_stats_on_failed (default: 0)

## Commands
- sm_stats
- sm_teamstats
- sm_resetstats (Admin - General Flag)

## Note
Work with L4D / L4D2.

## Installation
Put `chapter_statistical_report.smx` in `path/to/server/left4dead2/sourcemod/addons/plugins/<here>`\
cfg file will automatically generated in `path/to/server/left4dead2/cfg/sourcemod/l4d2_chapter_statistical_report.cfg`

## Version
1.1.1

## Changelog
```
2023-02-06 (v1.1.1)

* Hotfix 'Stats not resetting issue'.

2023-02-05 (v1.1.0)

* Reset command, 2 new cvars (csr_print_mode & csr_stats_on_failed).

2023-01-14 (v1.0.2) - Thanks to BloodyBlade

* Hotfix inconsistent indentation warnings, add newdecls required pragma, and change EventHook callback parameter from 'Handle' to 'Event'. 

2023-01-13 (v1.0.1)

* Hotfix 'Property "m_zombieClass" not found (entity 0/worldspawn)'. 

2023-01-12 (v1.0.0)

* Initial release.
```

## Screenshot
![](static/command.png)

## AlliedModders
https://forums.alliedmods.net/showthread.php?t=341241

## License
```
MIT License

Copyright (c) 2023 Tegar Bangun Suganda (OVERMIND)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
