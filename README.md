# FCL - Fileless Command Lines
Known command-lines of fileless malicious executions.

## Motivation

While hashing malicious files to identify malicious executions is easy, blocking the execution of fileless malware is more challenging.
This repository's purpose is to collect command lines being used by threat actors, to ease the difficult of identifying them.

## Structure

Each FCL file contains\may contain the following data:
* Malware name
* Executing process(es)
* Malicious command-lines (contain dysfunctional URLs)
* Fully\Partially deobfuscated command-lines
* Regular Expression for detection
* Technical write-ups
* Sandbox report links
* Notes

## Contributions
If you have any malicious related command line (deobfuscated or not), sandbox links, technical write-up, regular expression or any useful suggestion, please share it with me and I will update this repository accordingly.

## References
Here are some great references elaborating on fileless malicious executions and the use of it through time:
* https://docs.microsoft.com/en-us/windows/security/threat-protection/intelligence/fileless-threats
* https://blog.malwarebytes.com/threat-analysis/2018/08/fileless-malware-getting-the-lowdown-on-this-insidious-threat/
* https://zeltser.com/fileless-malware-beyond-buzzword/


## GPL 3
FCL - Fileless Command Lines Copyright (C) 2018, Chen Erlich.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.


## TODO
- [ ] Add more fileless malwares
- [ ] Sharp\add regular expressions

