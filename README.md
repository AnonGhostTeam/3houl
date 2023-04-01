Ghoul is a free and open-source tool available on GitHub. Ghoul is used as an information-gathering tool. This tool can be used to get information about our target(domain). We can target any domain using  Ghoul. The interactive console provides a number of helpful features, such as command completion and contextual help. This tool is written in python, so you must have python installed in your Kali Linux to use this tool. 

Ghoul is a python script to find admin login pages and EAR vulnerabilities. This tool uses different libraries, such as the Big path list (789 paths). Breacher tool supports PHP, asp JSP, and HTML extensions. Before scanning the web apps for the admin panel, it checks for robots.txt. This tool also supports custom paths and follows the technique of multi-threading on demand.

#### Features of Ghoul:
- [x] Before scanning website applications Ghoul Checks for potential EAR vulnerabilities.
- [x] Ghoul Checks for robots.txt before scanning.
- [x] Ghoul Support for custom paths to find admin panels.
- [x] Ghoul follows the technique of Multi-threading on demand.
- [x] Ghoul uses Big path list (798 paths).
- [x] Ghoul Supports php, asp and html extensions.
- [x] Ghoul is a python script to find admin login pages and EAR vulnerabilities
- [x] Ghoul is an open source tool you can download the tool for free.
- [x] Ghoul has interactive console provides a number of helpful features.

### Usages of Ghoul:
- Check all paths with php extension
```
python3 ghoul.py -u https://www.example.com --type php
```
- Check all paths with php extension with threads
```
python3 ghoul.py -u https://www.example.com --type php --fast
```
- Check all paths without threads
```
python3 ghoul.py -u https://www.example.com
```
- Adding a custom path. For example if you want all paths to start with /data (example.com/data/...) you can do this:
```
python3 ghoul.py -u https://www.example.com --path /data
```
<b>Note that: </b> When you specify an extension using <b>--type</b> option, Ghoul includes paths of that extension as well as paths with no extensions like <b>/admin/login</b>
