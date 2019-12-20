# MOS-tpot
A small malware organization script to organize files captured in the tpot honeypot

This basically will go through downloaded/captured files from a tpot cowrie instance and move those files into a well organized structure.
This allows for quicker and better analysis of the files as they are received. 

In tpot's current cowrie configuration, organization is a trivial task that takes a lot of time. 

This should aid in faster analysis of those files. 

----Use----

In your root directory execute:
`$ git clone https://github.com/whoAmI-cslim/MOS-tpot.git`

Once the complete execute:
`$ cd MOS-tpot`

Next simply execute the following command:
`$ bash Malware-Organizer.sh`

Upon completion, all files captured by cowrie in the download.tgz file will be organized by type. 

This is still a growing project. I only have current signatures identified for Crypto-Bots that constantly hit my honeypot. I plan to expand to additional signatures in the near future. 

