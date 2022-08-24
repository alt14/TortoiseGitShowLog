# TortoiseGitShowLog
QuickDrop Plugin for LabVIEW to bring up the TortoiseGit log for a VI, folder, library, class, repo etc. It's most useful if you set up TortoiseGit as your diff tool - you can right click on 1 or more log entries to diff. See [this NI Knowledge Article](https://knowledge.ni.com/KnowledgeArticleDetails?id=kA00Z0000019ZhbSAE&l=en-GB).

## Example Screenshot
This screenshot shows the TortoiseGit log launched from a LabVIEW VI. It is showing the log for that particular VI, which can then be diffed using a right-click menu.

[!Launching TortoiseGit Log from LabVIEW](/etc/screenshot_launch_log_LabVIEW.png)

## Required Software
 - Git
 - TortoiseGit
 - LabVIEW 2018 
    - A 2015 version can be installed but I didn't make this part of the repo
 - Windows OS

Tested on Windows 10, TortoiseGit 2.13.0.1 64-bit, Git version 2.35.3.windows.1 64-bit, LabVIEW 2018 32-bit.

## Installation
### VIPM VI Package (LabVIEW>=18.0)
 - Available [here](https://www.vipm.io/package/leah_edwards_lib_tortoisegit_show_log___quickdrop_plugin/).
### Alternative option for LabVIEW 2015, 2016, 2017
 - I backsaved but did not put this in the repo, see attachment to [post on NI forums](https://forums.ni.com/t5/Quick-Drop-Enthusiasts/TortoiseGit-Show-Log-QuickDrop-Shortcut/m-p/4249488).
### Manual Install
 - You can pull down this code and paste contents of source into *<LabVIEW 20xx>\resource\dialog\QuickDrop\plugins* or *&lt;LabVIEW Data>\Quick Drop Plugins*

## Instructions for Use
See [post on NI forums](https://forums.ni.com/t5/Quick-Drop-Enthusiasts/TortoiseGit-Show-Log-QuickDrop-Shortcut/m-p/4249488).