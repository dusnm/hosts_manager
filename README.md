# Hosts Manager
## A simple bash shell script to manage the GNU/Linux hosts file

### Warning!
This script was built for fun, it has not been tested for reliability, use at your own risk.

### Usage
* Listing the host file entries
```
./hosts_manager -l
```
* Appending a line
```
./hosts_manager -a "127.0.0.1 example.com"
```
* Deleting lines (comma separated)
```
./hosts_manager -d 3,7
```
