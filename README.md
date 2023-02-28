# Archived document

In actual production applications, important data often needs to be archived and backed up.

Requirement: Implement a daily archive backup script for the specified directory, enter a directory name (without a/at the end). Save all files in the directory by day and add the archive date to the archive file name in /root/archive.

The archive command: tar is used

You can add -c for archiving and -z for simultaneous compression, resulting in a file suffix of.tar.gz

