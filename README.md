CNC_XinFab 

Copy of the current XinFab CNC configuration files for Mach3.

Once downloaded, copy "CNC working.xml" and place it into your Mach3 program directory. Then it will appear in the Mach3 loader profile list, or you need to create a shortcut to run Mach3 with /p "path to .xml".

You may also need "1024.set".

Do NOT use "1024China.set", as it trashes core configuration items ... evnen though they should be held in "CNC working.xml".