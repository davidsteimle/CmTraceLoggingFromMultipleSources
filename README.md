# CmTrace Logging from Multiple Sources

CMTrace Logging from multiple sources to a single log file.

This is based largely on: https://adamtheautomator.com/building-logs-for-cmtrace-powershell/

-----

CMTrace is a fantastic way to utilize logs, and Adam's script was the jumping off point in creating the process I am using. I was, however, putting all the logging logic into a file which other files imported. Sadly, the "Component" field was always "ApplicationLogging.ps1" regardless of which script was using the function. I have added ``-Component`` as a paramater.

