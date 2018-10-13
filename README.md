# Web Video Streaming From Paspberry Pi

Streaming video from raspberry pi 3 to web browser.

Based on https://github.com/waveform80/pistreaming.git repository


## How to install and use

1. Mount pi camera module.
2. Install the extra libraries: 

    $ sudo apt-get install ffmpeg git python3-picamera python3-ws4py
   
3. Clone this repository to machine: 

    $ git clone https://github.com/waveform80/pistreaming.git
    
4. Run the server script: 

    $ python3 pistreaming/server.py
    
5. Open browser and visit the address http://pi-local-network-address:8082/
