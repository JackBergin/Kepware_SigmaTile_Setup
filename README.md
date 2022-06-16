# Kepware_SigmaTile_Setup
In this repository, there is the opf file for the kepware setup of the sigma tile. There is also the mfg-tile repository that is needed for the raspberry pi's environment. Clone this to the raspberry pi environment and run the install.sh file. Once completed, log into kepware, open up the opf file and then change the ip address linked under Channel1 to match the sigma tile's (listed upon execution of the main python script). To execute the Sigma Tile's main script navigate to the mfg-tile folder within the raspberry pi's terminal using cd. type the command "sudo python &lt;pythonfFile.py> and the IP address will be listed. Once this is completed, the sigma tile is connected to kepware. 

Connecting Kepware to Thingworx is the next step in order to create a GUI and Mashup for visualizing the data output from the Sigma Tile. The following link teaches the basics on connecting Kepware to Thingworx and takes very little time to get set up.
https://developer.thingworx.com/en/resources/guides/connect-kepware-server-thingworx-guide
