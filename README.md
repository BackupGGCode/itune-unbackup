#iTune-unbackup
Users of Apple mobile devices can perform a backup of them on their Mac or PC.  Directories and files are renamed, based on hash values.

These scripts will reverse the backup process so that the original directory structure is recreated and files are restored to their original file names. The script will recover potentially interesting data and identify all the sqlite databases in the backup.   The scripts are intended for use by forensic analysts and anyone interested in exploring the backups.

There are 3 scripts available: 2 python scripts for parsing the ICQ Free and ICQ Premium chat logs and a bash script for unbacking up the iTunes backups.

INSTRUCTIONS:

For Linux users only.  Make sure you have plutil and
sqlite3 installed - they should be available via your package manager.
You will also need the cleanlinks tool from the xutil-dev package.

1)  Copy the python code here:
> http://stackoverflow.com/a/8101937/2259311
> Save the code as mbdbparse.py in /usr/local/bin and
> make executable.
2)  Download my project scripts and copy to
> /usr/local/bin and make executable

3)  Run the ituneubkp.sc bash script - enter the location of your itune backup when
> prompted

THIS SCRIPT SHOULD ONLY BE RUN AGAINST A COPY OF YOUR ITUNES BACKUP
