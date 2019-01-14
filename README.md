# Plex and Torrenting seed box using docker

## TODO

    1. Explain the storage layout
    2. Explain how to bring it all together

## Installation

### 1. Ensure you have git installed

    sudo apt install git
 
### 2. clone this repository

    git clone https://github.com/doghousedean/cube-media-server.git

### 3. run the setup script

    cd cube-media-server
    sudo ./setup
 
### 4. Once finished you should have the following containers running and ready for use

    Plex, on port 32400, your streaming friend
    Sonarr, on port 8989, find some TV to download
    Jackett, on port 9117, a proxy between sonarr and torrent sites for search functions (Better than RSS)
    Portainer, on port 9000, cool container manager
    CouchPotato, on port 5050, find some movies to download
    Deluge, on port 8112, the best web based torrenter I can find
    Watchtower, keeps all your containers up to date
