# Checking Disk Space

* `df -h` - Human readable amount of disk space used on each drive.
* `du --max-depth 5 / | sort -n` - returns the largest folders on disk
* `find /tmp/pompeius/ -type d -mtime +3 | xargs rm -rf` - Find all folders that have not bee modified in 3 days and remove them.
