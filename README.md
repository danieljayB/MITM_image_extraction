MITM_image_extraction
=====================

<h2> About </h2>

Bash script implementing a MITM attack with Ettercap & image extraction from intercepted packets with Driftnet. 
Port forwarding setup within script.  

<h2> foreword </h2>

Tested on the Raspberry Pi "Rasbian" image. Due to the nature of this program continously writing new image files, I have formatted the code to write to an external HDD connected to the Raspberry Pi.  

Execute from the script : ```. MITM-image-extraction.sh``` to prevent running script in the child shell.

<h2>Dependencies</h2>

ettercap & driftnet. Stricly intended for personal research. :grimacing:
