# whatsapp_hack
Hack whatsapp web via a cloned website

## disclamer

THIS IS FOR DEMONSTRATIVE PURPOSES ONLY.

DO NOT USE ON REAL VICTIMS FOR ANY REASON. CRIMINAL LAW WILL APPLY.
 
install the requirements

    cd path/to/the/repo
    pip install -r requirements.txt
    
first run the grabber
    
    python3 grabber.py
    
then run the server

    python3 server.py
    
    
as the victim scans the qr on the fake website, whatsapp web on the browser spawned
by the grabber will be connected to the victim's number.

## Before usage:
 - change the last line of the server.py script to fit your needs
 (if run on port 80, you might need to run as superuser)
 - router configuration might be necessary (port mapping)