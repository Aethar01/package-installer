# package-installer

A simple script that installs packages on steam deck/arch linux.

## Installation
```bash
git clone {this repo}
cd package-installer
cp package-installer ~/.local/bin/
```

## Usage

```bash
package-installer
```

To dry run the script, use

```bash
DRYRUN=1 package-installer
```

## Configuration

The packages to install are listed in ~/.config/package-installer/packages.list
Both the arch linux and AUR package lists are supported.

Each line in the file should be a package name, e.g.

```
package1
package2
package3
```
