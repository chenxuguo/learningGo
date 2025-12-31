# Install Remote Desktop (xRDP) for Ubuntu Server 18.04

## Step 1 – Install xRDP:

    sudo apt update
    sudo apt install xrdp

## Step 2 – Install XFCE4

    sudo apt install xfce4
    sudo apt-get install xfce4-terminal tango-icon-theme

## Step 3 - Configure

    echo xfce4-session > ~/.xsession

## Step 4 - Restart xRDP

    sudo service xrdp restart


## Step 5 - Testing

On Windows PC, use `mstsc` to connect to the ubuntu server
