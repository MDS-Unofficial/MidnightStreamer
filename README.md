		 	__  __ _     _       _       _     _   ____  _                                      
			|  \/  (_) __| |_ __ (_) __ _| |__ | |_/ ___|| |_ _ __ ___  __ _ _ __ ___   ___ _ __ 
			| |\/| | |/ _` | '_ \| |/ _` | '_ \| __\___ \| __| '__/ _ \/ _` | '_ ` _ \ / _ \ '__|
			| |  | | | (_| | | | | | (_| | | | | |_ ___) | |_| | |  __/ (_| | | | | | |  __/ |   
			|_|  |_|_|\__,_|_| |_|_|\__, |_| |_|\__|____/ \__|_|  \___|\__,_|_| |_| |_|\___|_|   
					                        |___/                                              ®

			     [Installation instructions for MDS v5.9.1 - Lifetime]

                                        =======================                                     
                                        = =====================                                     
                                        = =========    ========                                     
                                        = =====================                                     
                                        = =========    ========                                     
                                        = =====================                                     
                     =======            = =====================                                     
                  ====     ====         = =========    ========               ========              
                ===           =======   = =====================            ====      ===            
          ======                        = =========    ========    ==== ====           ====         
     =====      =======                 = =====================                                     
                                        =     ===========    ==                                     
                                        = ============= =======                       ===           
                   ===================  =     ===========    ==               ===  ===   =====      
                  ===================== = =====================                                     
                  ===================== =     =============================                         
                  ===================== = ======== =========================                        
                  ===================== =          ==                   ====                        
                  ===================== =          ==                   ====                        
                  ===================== =    ====  ==            =================                  
                  ===================== =  ==    ====            ===   == ========                  
                      =========== ==    ====       ==            =======        ==                  
         ======   ==                  ==           ==            =================                  


<br />
<img width="1000" alt="Screenshot 2026-04-03 093752" src="https://github.com/user-attachments/assets/5b8a243f-49be-404c-b852-c00a45c20044" />

<img width="1000" alt="Screenshot 2026-04-03 095152" src="https://github.com/user-attachments/assets/76ee7bf9-969f-47fb-ac2b-3b3b930fc007" />
<br />
The fastest and most reliable passthrough streaming on the planet. Instant on-demand stream open even from cold sources (encoders, multicast, dvb headends) and from multiple hops.


## Ubuntu versions
* Tested on **Ubuntu 18/20/22/24/26**

## PHP
* On Ubuntu 20/22/24/26 PHP version **8.3.36** (CVE patches, Oct 2026)
* On Ubuntu 18 (GLIBC <= 2.29) PHP version **7.4.34** (CVE patches, Oct 2026)

## Installation
1. Download and extract the zip file https://mega.nz/folder/nIhFlYhY#7nNP5mZexcOqg3di9vHNOQ 


2. Install the panel (Reboot your server once before running the installer to make sure the dpkg pid is not locked, even on fresh OS installations)
	 
	```
	chmod +x ms_install_offline.sh

	./ms_install_offline.sh
	```


3. [Optional]

	```
	echo -e "\n127.0.0.1 download.midnightstreamer.com" >> /etc/hosts
	```


4. Login to the panel and make sure the server IP address is correct in the server settings (LB installations will fail if the main server does not have a reachable IP configured)

**Enjoy**

To boost performance in case of 12k+ concurrent clients on a single LB increase the Total FastCGI Services in the server settings.

This distribution is a reinstall backup for those using v5.9.1. This repository will be updated from time to time only for security purposes.

The active v8 branch can be found here <a href="https://discord.gg/xwJwZCH6H">https://discord.gg/xwJwZCH6H</a>

* <a href="https://github.com/MDS-Unofficial/MidnightStreamer">Github</a>

<div style="visibility: hidden">Midnight Streamer | MDS</div>
