# Dropbox Notesync using the Python SDK 

A practical project to fight atrophe
---
Wanted a quick n' dirty way to backup stuff on my linux box, thought it'd be fun to hit the dropbox v2 api via the python sdk.

### Usage

I use [autokey](https://github.com/autokey-py3/autokey) for both autopasting and keeping notes. The dropbox_notesync.py script will back up everthing you have in your autokey automatically, as long as you've kept the defaults for autokey. 

The dropbox_misc-backup.py script needs to have 'actual-src' and 'actul-dst' replaced with the actual src and dst file/directory that you want to backup - There's 2 copy methods there, a single file and single directory.
