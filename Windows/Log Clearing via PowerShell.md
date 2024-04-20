_NOTE: Some of the fields that are being used may be different in your environment depending on parsing._ 

### Clearing Logs via PowerShell: 
`vendor:"Microsft" AND process_name:("powershell.exe", "pwsh.exe", "powershell_ise.exe") AND process_command_line:"Clear-EventLog"`

Inspiration/Reference:https://elastic.github.io/detection-rules-explorer/rules/d331bbe2-6db4-4941-80a5-8270db72eb61
