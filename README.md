# my-google-dorks-cybersec
A list of all the google dorks I use for pentesting recon.

### +++ Publicly Exposed Documents +++

`site:site.com ext:doc | ext:docx | ext:odt | ext:rtf | ext:sxw | ext:psw | ext:ppt | ext:pptx | ext:pps | ext:csv`

### +++ Directory listing vulnerabilities +++

`site:site.com intitle:index.of`

### +++ Exposed config files +++ 

`site:site.com ext:xml | ext:conf | ext:cnf | ext:reg | ext:inf | ext:rdp | ext:cfg | ext:txt | ext:ora | ext:ini | ext:env`

### +++ Exposed Database Files +++

`site:site.com ext:sql | ext:dbf | ext:mdb`

### +++ Exposed Log Files +++

`site:site.com ext:log`

### +++ Backup and old files +++

`site:site.com ext:bkf | ext:bkp | ext:bak | ext:old | ext:backup`

### +++ Login Pages +++

`site:site.com inurl:login | inurl:signin | intitle:Login | intitle:"sign in" | inurl:auth`

### +++ SQL Errors +++

`site:site.com intext:"sql syntax near" | intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning: mysql_query()" | intext:"Warning: pg_connect()"`

### +++ PHP Errors/Warning +++

`site:site.com "PHP Parse error" | "PHP Warning" | "PHP Error"`

### +++ phpinfo() +++

`site:site.com ext:php intitle:phpinfo "published by the PHP Group"`

### +++ Search pastebin sites +++

`site:pastebin.com | site:paste2.org | site:pastehtml.com | site:slexy.org | site:snipplr.com | site:snipt.net | site:textsnip.com | site:bitpaste.app | site:justpaste.it | site:heypasteit.com | site:hastebin.com | site:dpaste.org | site:dpaste.com | site:codepad.org | site:jsitor.com | site:codepen.io | site:jsfiddle.net | site:dotnetfiddle.net | site:phpfiddle.org | site:ide.geeksforgeeks.org | site:repl.it | site:ideone.com | site:paste.debian.net | site:paste.org | site:paste.org.ru | site:codebeautify.org  | site:codeshare.io | site:trello.com "site.com"`

### +++ Search github and gitlab +++

`site:github.com | site:gitlab.com "site.com"`


### +++ Search stackoverflow.com +++

`site:stackoverflow.com "site.com"`

### +++ Signup Pages +++

`site:site.com inurl:signup | inurl:register | intitle:Signup`

### +++ Find Subdomains +++

`site:*.site.com`

### +++ Find Sub-Subdomains +++

`site:*.*.site.com`

### +++ Search in Wayback Machine +++

`https://web.archive.org/web/*/site.com/*`

### +++ Show only IP addresses (opens multiple tabs) +++

`(site.com) (site:*.*.29.* |site:*.*.28.* |site:*.*.27.* |site:*.*.26.* |site:*.*.25.* |site:*.*.24.* |site:*.*.23.* |site:*.*.22.* |site:*.*.21.* |site:*.*.20.* |site:*.*.19.* |site:*.*.18.* |site:*.*.17.* |site:*.*.16.* |site:*.*.15.* |site:*.*.14.* |site:*.*.13.* |site:*.*.12.* |site:*.*.11.* |site:*.*.10.* |site:*.*.9.* |site:*.*.8.* |site:*.*.7.* |site:*.*.6.* |site:*.*.5.* |site:*.*.4.* |site:*.*.3.* |site:*.*.2.* |site:*.*.1.* |site:*.*.0.*)`

### Credits
COURTESY OF 
pentest-tools.com/information-gathering/google-hacking




