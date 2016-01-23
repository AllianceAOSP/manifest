BaseRom 
=====================

Getting Started
---------------

To build BaseRom from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/BaseROM/manifest.git -b mm

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) make otapackage
    
