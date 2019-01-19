# sslScrape
SSLScrape | A scanning tool for scaping hostnames from SSL certificates.
Written by Peter Kim <Author, The Hacker Playbook> and @bbuerhaus
                     <CEO, Secure Planet LLC>

  _________ _________.____       _________                                  
 /   _____//   _____/|    |     /   _____/ ________________  ______   ____  
 \_____  \ \_____  \ |    |     \_____  \_/ ___\_  __ \__  \ \____ \_/ __ \ 
 /        \/        \|    |___  /        \  \___|  | \// __ \|  |_> >  ___/ 
/_______  /_______  /|_______ \/_______  /\___  >__|  (____  /   __/ \___  >
        \/        \/         \/        \/     \/           \/|__|        \/ 

Usage | python sslScrape.py [CIDR Range]
E.X   | python sslScrape.py 10.100.100.0/24
 
## Installation:

1. Install masscan: apt install masscan
2. Create a python virtualenv (https://virtualenv.pypa.io/en/stable/) for sslScrape and activate it
   python -m virtualenv sslscrape
   source sslscrape/bin/activate
3. pip install -r requirements.txt
