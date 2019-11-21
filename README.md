# Example GitHub repo for Collections that don't have their own home.

This repo will be the default location of Collections that don't have another home.

All Collections will be release on the same schedule by the Community Team.

## Contents

There are a lot of (groups of) modules that:
* don't currently need their own release cycle
* don't have an active Working Group
* may have a working group, though they don't want the overhead of maintaining their own Repo or Collection release cycles

Collections are defined at the sub-topic level (ie mysql, gitlab, zabbix).
Modules from ansible/ansible that aren't in a subdirectory will be created as a Collection with just a single module, see monitoring/nagios.

Directory structure that matches the previous Ansible topics (Cloud, Database, Identity, etc) is used to help organise the repo

## Example Collection


Directory: `database/mysql/` 
Collection: `community.mysql`

Example of a single module previouly under a toplevel directory (`lib/ansible/modules/monitoring/nagios.py`) in a collection on it's own.
Directory: `monitoring/nagios`
Collection: `community.nagios`

## Notes

*WARNING* This is a proof of concept for Ansible Community Collection development workflow.

For more information see `#ansible-community` on Freenode IRC.

## License

GNU General Public License v3.0 or later

See LICENCING to see the full text.
