Autohotkey Media custom key
===

# Prerequisites

- Windows OS 7, 8, 8.1, 10
- Authotkey
- Admin access

# Installation

First, install Autohotkey. 

Get the repository :

```
git clone https://github.com/Nickael/autohotkeys_script.git
```

Then select **media.ahk** > right click > Compile script.

Enjoy.

# Keys

```
Win+Alt+Down    = Pause, Play media
Win+Alt+Left    = Preview media
Win+Alt+Right   = Next media
```

# Script

```
#!Down::Send       {Media_Play_Pause}
#!Left::Send        {Media_Prev}
#!Right::Send       {Media_Next}
```