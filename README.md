# custom_debian

Custom Debian distribution based on live-build.


    sudo apt install live-build
    mkdir custom_debian
    cd custom_debian
    lb config --distribution trixie --architectures amd64 --archive-areas "main contrib non-free non-free-firmware"
    # After run the config command, don't forget change the mirror
    sudo lb build
    lb clean
