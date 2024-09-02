# Windows
* Find the full path to the claude-engineer directory. Let's assume it's located at `C:\path\to\claude-engineer`
* Add this directory to your system's PATH:
    * Right-click on the Start button and select "System".
    * Click on "Advanced system settings" on the right side.
    * In the System Properties window, click the "Environment Variables" button.
    * In the "System variables" section, find the "Path" variable and click "Edit".
    * Click "New" and add the full path to the claude-engineer directory: `C:\path\to\claude-engineer`
    *Click "OK" on all windows to save the changes.

# Linux / Mac
* Find the full path to the claude-engineer directory. Let's assume it's located at `C:\path\to\claude-engineer`
* Create a symbolic link to the main script in a directory that's already in your PATH, like /usr/local/bin:
`sudo ln -s /path/to/claude-engineer/main.py /usr/local/bin/claude-engineer`