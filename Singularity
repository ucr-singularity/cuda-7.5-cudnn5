Bootstrap: docker
From: nvidia/cuda:7.5-cudnn5-devel-ubuntu14.04

%post

    # Update list of available packages, then upgrade them
    apt-get update
    DEBIAN_FRONTEND=noninteractive apt-get -y upgrade
