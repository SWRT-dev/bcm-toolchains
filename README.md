1. `git clone https://github.com/MerlinRdev/bcm-toolchains`

2. `cd bcm-toolchains`

3. `sudo mkdir -p /opt/toolchains/`
 
    `sudo ln -sf $(pwd)/hndtools-arm-linux-2.6.36-uclibc-4.5.3 /opt/toolchains/`

    `sudo mkdir -p /projects/`
    
    `sudo mkdir -p /projects/bca/`
    
    `sudo mkdir -p /projects/bca/tools/`
    
    `sudo mkdir -p /projects/bca/tools/linux/`
    
    `sudo mkdir -p /projects/bca/tools/linux/bin/`
    
    `sudo ln -sf $(pwd)/hndtools-armeabi-2013.11 /projects/bca/tools/linux/`
    
    `sudo ln -sf $(pwd)/fwtag.ini /projects/bca/tools/linux/bin/`
    
    `sudo ln -sf /projects/bca/ /projects/hnd/`

