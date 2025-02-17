CHANGELOG
=========

# Version History

## 0.9.1
15.11.2019
* Move a comment that states that --fetch-full-installer is available to the correct place (#31)

## 0.9.0
07.10.2019
* Added support for `softwareupdate --fetch-full-installer` and `seedutil` for clients running macOS 10.15 or greater.

## 0.8.0
27.09.2019
* Fixed caffeinate (forgot to make it a background process)
* Added 'Confirm' option for erasing. Thanks to '@ryan-alectrona' for the contribution.

## 0.7.1
26.09.2019
* Added caffeinate to the script to prevent the computer going to sleep during long download phases etc.

## 0.7.0
12.07.2019
* Added `--beta` option.
* Changed behaviour of `--os`, `--version` and auto (i.e. no flag) options to get the latest rather than earliest valid build.
* Removed `install-macos.sh` script. Use `erase-install.sh` with `--reinstall` option instead.

## 0.6.0
19.06.2019
* Added `--reinstall` option, which obsoletes the `install-macos.sh` script.

## 0.5.0
16.04.2019
* Bug fix for empty extra packages folder.  
Thanks to '@Avartharian' for contributions
* Added `--catalogurl` and `--seedprogram` options

## 0.4.0
02.04.2019  
* Added localisation of Jamf Helper messages.  
Thanks to '@ahousseini' for contributions
* Added `--os`, `--path`, `--extras`, `--list` options.  
Thanks to '@mark lamont' for contributions

## 0.3.2
13.12.2018  
* Bug fix for `--build` option, and for exiting gracefully when nothing is downloaded.

## 0.3.1
21.09.2018  
* Added ability to specify a macOS version.  
* Fixed the `--overwrite` flag.  
* Added ability to specify a build in the parameters, and we now clear out the cached content.

## 0.3.0
03.09.2018  
* Additional and amended options for selecting non-standard builds.

## 0.2.0
09.07.2018  
* Automatically selects a non-beta installer.

## 0.1.0
29.03.2018  
* Initial version. Expects a manual choice of installer from `installinstallmacos.py`.
