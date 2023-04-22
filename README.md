# backup
easily copy data between hard drives that have connection issues

## Description
This script lets you copy files and directories, using rsync, between one or even two hard drives, and will restart if the drives are unplugged and replugged for some reason.

## Environment
Only tested on MacOS Ventura. Ubuntu support is in the works.

## Examples
Copy all files from the drive located at `/dev/disk3s1` to a backup directory at `/backups`, with a timeout of 1 hour:
```
./backup -s /dev/disk3s1 -d /backups -t 60
```

For more options, run `./backup --help`.

## Author
- [Sean Reid](mailto:seanreid.mail@gmail.com)
