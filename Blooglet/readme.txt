
Before installing the SysDeb Patched SOF Driver, you need to do the following:

Run Command Prompt as an Administrator. You may do so by pressing the Windows/Start key and typing cmd, and clicking on the button that says "Run as Administrator."

Then, you may copy and paste the lines below. ONLY DO SO IF YOU KNOW WHAT YOU ARE PASTING.

bcdedit /set testsigning on
bcdedit /set nointegritychecks yes

After doing that, you may close the Command Prompt Window. Do not open dpinst.exe as this hasn't been patched yet.

Instead, right-click on csaudiointcsof.inf and click on the option that says "Install".