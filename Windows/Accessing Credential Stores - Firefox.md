_NOTE: Some of the fields that are being used may be different in your environment depending on parsing._ 

### Accessing Credential Stores - Firefox: 
`vendor:"Microsoft" AND (process_command_line:RGXi("Copy-Item \$env\:APPDATA\\Mozilla\\Firefox\\Profiles") OR scriptblock_text:RGXi("Copy-Item \$env\:APPDATA\\Mozilla\\Firefox\\Profiles"))`

Inspiration/Reference: https://www.elastic.co/guide/en/security/current/access-of-stored-browser-credentials.html, https://attack.mitre.org/techniques/T1555/003/
