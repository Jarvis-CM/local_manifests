Jarvis Manifest
===============

Here is all you need!

Getting Started
---------------

To get started with Android/CyanogenMod and especially J.A.R.V.I.S, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the CyanogenMod trees and Jarvis repositories, use a command like this:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0

Then copy jarvis.xml into .repo/local_manifests folder in your cm11.0 tree

After that, to sync up:

    repo sync
    
If you noticed bugs or other problems of have suggestions just fill a bug report or make comments!
