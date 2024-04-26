---
layout: manual-page
title: 5 Collecting Logs
---

# Collect Launcher Logs
This page will guide you through the process of collecting launcher logs. These will assist developers with helping you troubleshoot the launcher.

## Table of Contents
1. [Capturing Launcher Logs (Windows)](#capturing-launcher-logs-windows)

## Capturing Launcher Logs (Windows)
If the launcher is able to make it past the login screen, the launcher logs are available in the Launcher Log tab (as seen in [Figure 1](#fig01)). Otherwise, follow the steps below.

<span class="manual-figure" id="fig01">
<a href="img/05/fig01-launcher-logs.png"><img alt="Launcher Log tab" src="img/05/fig01-launcher-logs.png" /></a><br>
**Figure 1**: Launcher Log tab
</span>

1. Open the Command Prompt.
   
   You may use `Win+R` to open the **Run** window and enter `cmd`, then press enter.

   <span class="manual-figure" id="fig02">
   <a href="img/05/fig02-run-window.png"><img alt="Run window" src="img/05/fig02-run-window.png" /></a><br>
   **Figure 2**: Run window
   </span>

2. Run `java -jar C:\path\to\olauncher.jar`.
   
   As a shortcut, you may enter the full path of the jarfile by dragging it onto the Command Prompt window.

3. Reproduce the issue.

4. Select and copy logs from Command Prompt.
   
   You may use right-click to copy selected text.
   
   The launcher logs will now be on your clipboard. You may paste them into a text file or send them on Discord.

