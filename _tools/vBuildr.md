---
title: vBuildr
---

## vBuildr Options/Commands

```

Usage:
  vbuildr.exe [OPTION…] - Vala make/builder

Help Options:
  -h, --help                         Show help options
  --help-all                         Show all help options
  --help-install                     Show install options

Install options:
  --bldifldr=PATH_INSTALL_PREFIX     Build package installation folder,none=no install
  --projpkg                          Project name
  --desc                             Project description
  --pkgver=SEMVER                    Package version SEMVER(`MAJOR.MINOR.PATCH`)
  --codever=SEMVER                   Code/Module version SEMVER(`MAJOR.MINOR.PATCH`)

Application Options:
  --define=DEFINE...                 Preprocessor defines
  --outtype=OUTTYPE                  OUTTYPE(`exe`,`static`,`shared`)
  --maxerrs                          Stop compiling when max errors
  --oname=NAME                       Link output name 
  --pkg=PKG...                       Vala packages or '*.vapi'
  --pkgcfg=PKG-CONF                  pkg-config command
  --srcdir=SRCDIR...                 Source directories default=src
  --vapidir=DIRECTORY...             Look for package bindings in DIRECTORY, default=env[PKG_CONFIG_PATH]
  --version                          Display version number
  --vflag=VFLAG...                   Vala flags
  --cflag=CFLAG...                   gcc/cc flags
  --cc=COMPILE                       Use COMPILE as compiler command
  --ar=ARCHIVE                       Use ARCHIVE as archive command
  -a, --action=ACTION                ACTION(`build`,`clean`,`report`,`install`,`uninstall`)
  -b, --bindir=BINLIB                Bin/Lib directory
  -o, --objdir=OBJ                   Objects directory default=obj
  -p, --projdir=DIRECTORY            Project directory default=PWD
  -t, --type=BTYPE                   BTYPE(`P[rod],D[ebug],T[est]`)
  -v, --verbose                      Print additional messages to the console
  --theme=THEME                      THEME(`none`,`light`,`dark`)
  --log=<prefix>%003d.log            Log to filename

Email:osstekz@gmail.com
Copyright © 2016-2020 George Aslanis

```
