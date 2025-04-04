# vhost_add.ps1 Documentation

## Prerequisites

- **Administrative Privileges**: Modifying the `hosts` file requires elevated permissions. The script includes functionality to relaunch itself with administrative rights if not already running as an administrator.

## Usage Instructions

1. **Save the Script**: Save the `vhost_add.ps1` 

2. **Run the Script**:
   - Open PowerShell.
   - Navigate to the directory containing the `vhost_add.ps1` script.
   - Execute the script by typing `.\vhost_add.ps1` and pressing Enter
   - Alternatively just right click on icon and select `Run with PowerShell`

3. **Provide Input**:

4. **Script Execution**:
   - The script will check if it's running with administrative privileges. If not, it will attempt to relaunch itself with the necessary rights.
   - It will then verify if the provided entry already exists in the `hosts` file.
   - If the entry does not exist, the script will append it to the `hosts` file.
   - After updating, the script will open the `hosts` file in Notepad for review.
   - Finally, the script will prompt you to decide if you want to add another entry.

