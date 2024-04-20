_NOTE: Some of the fields that are being used may be different in your environment depending on parsing._ 

### Accessing Credential Stores - Edge: 
`vendor:"Microsoft" AND (process_command_line:RGXi("Copy-Item \$env\:LOCALAPPDATA\\Microsoft\\Edge\\User Data\\Default") OR scriptblock_text:RGXi("Copy-Item \$env\:LOCALAPPDATA\\Microsoft\\Edge\\User Data\\Default"))`

Inspiration/Reference: https://attack.mitre.org/techniques/T1555/003/
