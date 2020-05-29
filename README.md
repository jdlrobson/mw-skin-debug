# mw-skin-debug

This is a skin for developers to track the changes in the skin system documented in the RFC https://phabricator.wikimedia.org/T249673

## setup

* Install Vector.
* Check out https://gerrit.wikimedia.org/r/592790.
* Install this skin in a folder skins/Debug
* Add the following to LocalSettings.php
```
wfLoadSkin('Debug')
```
* Visit any page with ?useskin=debug to see associated skin data.
