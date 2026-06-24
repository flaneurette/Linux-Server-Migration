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

```
sudo add-apt-repository ppa:flaneurette/smash
sudo apt update
sudo apt install smash
smash -v
```