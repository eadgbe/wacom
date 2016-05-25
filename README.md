#wacom

Workaround to the memory leak listed here:

http://forum.wacom.eu/viewtopic.php?f=4&t=20807

Because running powershell scripts are disabled on Windows by default, use the following command to bypass it:

powershell -ExecutionPolicy ByPass -File services_restart.ps1
