# -linux-dev
this will contain all the frequently used commands for linux. 

## Linux Frequently used commands

### [check current linux os](https://www.cyberciti.biz/faq/how-to-check-os-version-in-linux-command-line/)
#### *command 1:* 
---
```
cat /etc/os-release
```
#### *Sample output:*
---
```
NAME="Ubuntu"
VERSION="20.04.6 LTS (Focal Fossa)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 20.04.6 LTS"
VERSION_ID="20.04"
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
VERSION_CODENAME=focal
UBUNTU_CODENAME=focal
```
---
#### *Command 2:* 

```
lsb_release -a
```
#### *Sample output:*
```
    No LSB modules are available.
    Distributor ID: Ubuntu
    Description:    Ubuntu 20.04.6 LTS
    Release:        20.04
    Codename:       focal
```
---
#### *Command 3:* 
```
hostname
````
#### *Sample output:*
```
workspacef4984c1a4a044978-c4d5984d5-wrfpb
````
---
#### *Command 4:* 
```
uname -r
```
Sample Output:
```
Linux codespaces-a999d4 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
---
### check which os architecture
```
uname -m
```
sample output:
```
x86_64
```
---
### check how much free ram is available
```
free -m
```
sample output:
```
     total        used        free      shared  buff/cache   available
Mem:       16364604     1465088     5239896       68464     9659620    14476336
Swap:             0           0           0
```




