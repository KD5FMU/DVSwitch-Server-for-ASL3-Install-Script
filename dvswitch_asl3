#!/bin/bash

# This is a simplified install script for DVSwitch Server for AllStarLink 3 created by 
# Freddie Mac - KD5FMU
# Created November 21st 2024

# Install package dependencies for DVSwitch
echo "Package Depend for DVSwitch..."
sudo apt install php-cgi libapache2-mod-php8.2
echo "Apache2 for DVSwitch Installed..."

# Install DVSwitch Server
echo "Installing DVSwitch Server..."
cd ~
sudo wget dvswitch.org/bookworm
sudo chmod +x bookworm
sudo ./bookworm
sudo apt update
sudo apt install -y dvswitch-server
echo "DVSwitch Server installed."
