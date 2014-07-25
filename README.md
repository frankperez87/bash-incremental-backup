# BASH Incremental Backup Tool
Easily backup files from one location to another. Old files that have changed are stored in a hidden folder .FPBACKUP

**Example Usage:**
* * *
##### Create Symlink to your ~/bin directory
```
ln -s src/fpbackup ~/bin/fpbackup
chmod +x src/fpbackup
```

##### To start the backup tool in interactive mode use as follows
```
fpbackup
```

##### To run the backup tool skipping the prompts, define them as such
```
fpbackup /path/to/source_directory /path/to/backup/folder 1024
```

##### To use this tool, in order to backup to a remote location use as such
```
fpbackup /path/to/source_directory user@server:/path/to/backup/folder 1024
```

**Note, that in order for this to work you must use SSH keys for authentication.**
