With Raspberry Pi, clone this project with git clone in terminal
or download the zip file directly and unzip.
There will be two files, explained below:

<h1>1. installer.py</h1>
Use this to install python package to RoboRio.

## Usage


Updating package call:

python3 installer.py download-robotpy download-opkg python36-robotpy-ctre

Install on RoboRio:

python3 installer.py install-robotpy install-opkg python36-robotpy-ctre

<h1>2. requirements.txt</h1>
Install other required packages on to Raspberry Pi

## Usage

pip3 install -r requirements.txt
