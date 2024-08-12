# Windows PowerShell Configuration and Command Usage

## Overview

This repository showcases various tasks performed in configuring and using Windows PowerShell. The exercises cover configuring the PowerShell console and Integrated Scripting Environment (ISE), finding and running PowerShell commands, and using About files for help.

## Contents

- **[Exercise 1](#exercise-1-configuring-the-windows-powershell-console)**: Configuring the Windows PowerShell Console
  - Task 1: Starting and Pinning Windows PowerShell as Administrator
  - Task 2: Configuring the PowerShell Console Appearance and Layout
  - Task 3: Starting a Shell Transcript

- **[Exercise 2](#exercise-2-configuring-the-windows-powershell-ise)**: Configuring the Windows PowerShell ISE
  - Task 1: Opening Windows PowerShell ISE as Administrator
  - Task 2: Customizing ISE Appearance and Layout

- **[Exercise 3](#exercise-3-finding-and-running-powershell-commands)**: Finding and Running PowerShell Commands
  - Task 1: Finding Commands for Specified Tasks
  - Task 2: Running Commands to Accomplish Tasks

- **[Exercise 4](#exercise-4-using-about-files)**: Using About Files
  - Task 1: Locating and Reviewing About Help Files

---

## Exercise 1: Configuring the Windows PowerShell Console

### Task 1: Starting and Pinning Windows PowerShell as Administrator

1. Open the Start menu and search for `powershell`.
2. Right-click `Windows PowerShell` and select `Run as administrator`.
3. Pin the Windows PowerShell icon to the taskbar.

### Task 2: Configuring the PowerShell Console Appearance and Layout

1. Right-click the title bar of the PowerShell window and select `Properties`.
2. **Font Configuration**:
   - Select the `Font` tab.
   - Choose `Consolas` and set the size to `16`.
3. **Color Configuration**:
   - Select the `Colors` tab and experiment with color combinations for better readability.
4. **Layout Configuration**:
   - Adjust `Width` and `Height` under `Window Size` to fit within the preview area.
   - Set `Screen Buffer Size` width to match the `Window Size` width.

### Task 3: Starting a Shell Transcript

Run the following command to start a transcript:

```powershell
Start-Transcript C:\DayOne.txt
