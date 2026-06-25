# Linux Server-Migration with Smash
Migrate entire linux servers easily with a SMASH based transpiler.

Attached two .smash files:

- migration-export.smash
- migration-import.smash

Make a linux server backup easily and import everything on a blank (Ubuntu) server, 
in under ten minutes. Full installation and a working copy. Also useful to create mirrors.

If you don't know what SMASH is, it is a JavaScript to Bash transpiler.

To install SMASH:

https://github.com/flaneurette/SMASH

Install:

```
1. Download the .deb file
wget https://github.com/flaneurette/SMASH/raw/refs/heads/main/builds/smash_1.3-0_all.deb

2. Install the package
sudo dpkg -i smash_1.3-0_all.deb

3. Run SMASH
smash -v
```

Or use the Ubuntu PPA (does not have the lastest version!)

```
sudo add-apt-repository ppa:flaneurette/smash
sudo apt update
sudo apt install smash
smash -v
```