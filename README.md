Pixel Dust Project Manifest
===========================

To initialize your local repository use

    repo init -u https://github.com/pixeldustproject/manifest.git -b n
    mkdir .repo/local_manifests
    cp .repo/manifests/local_manifests/pixeldust.xml .repo/local_manifests/
    
Then to sync up:

    "repo sync -jX" where X is the number of cores in your CPU

