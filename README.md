# tmrecovery
Time Machine Recovery


Pocedure to recover specific files using this script:

1. Mount time machine drive on your ubuntu systme
2. copy this tmrestore.sh to /usr/local/bin/tmrestore.sh
3. Execute following command to restore files from Destop. Use this as reference
   $ sudo -i 
   $ /usr/local/bin/tmrestore.sh /media/user_name/mount_point/.HFS+(tab) /home/user_name/Desktop/backup/ /media/user_name/mount_point/Backups.Backupdb/old_pc_name/Latest/Macitosh\ HD/Users/Desktop Desktop(new folder in backups)

4. Restore iCloud Drive data
   $ /usr/local/bin/tmrestore.sh /media/path_to_.HFS+(using tab) /home/path_to_backup_folder/ /media/path_to_latestBackup/Users/Library/Mobile\ Documents iCloud(new Folder)
