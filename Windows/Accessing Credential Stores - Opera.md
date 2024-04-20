_NOTE: Some of the fields that are being used may be different in your environment depending on parsing._ 

### Accessing Credential Stores - Opera: 
`vendor:"Microsoft" AND (process_command_line:RGXi("Copy-item \$env\:APPDATA\\Opera Software\\Opera Stable\\Login Data") OR scriptblock_text:RGXi("Copy-item \$env\:APPDATA\\Opera Software\\Opera Stable\\Login Data"))`

Inspiration/Reference: https://attack.mitre.org/techniques/T1555/003/
