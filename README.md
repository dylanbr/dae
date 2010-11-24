dae
===

Synopsis
--------
`dae [-a] | [-l] | [-L] | <service-name>[+|-|=|?| action]... | [-h]`

Description
-----------
*dae* program is used to control or list available daemons on the system.

Shortcuts are provided for often used actions start, stop, restart and status.

Examples
--------
`dae apa restart`
Restart *apache* using daemon name expansion.

`dae sshd+`
Start *sshd* using a shortcut operator.

`dae apa= my= apa? my?`
Restart *apache* and *mysqld* and then request a status from both.
