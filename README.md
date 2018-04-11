# nmappy
Automating and Enhancing Nmap using Python

     .-') _ _   .-')      ('-.      _ (`-.    _ (`-.             
    ( OO ) | '.( OO )_   ( OO ).-. ( (OO  )  ( (OO  )            
,--./ ,--,' ,--.   ,--.) / . --. /_.`     \ _.`     \ ,--.   ,--.
|   \ |  |\ |   `.'   |  | \-.  \(__...--''(__...--''  \  `.'  / 
|    \|  | )|         |.-'-'  |  ||  /  | | |  /  | |.-')     /  
|  .     |/ |  |'.'|  | \| |_.'  ||  |_.' | |  |_.' (OO  \   /   
|  |\    |  |  |   |  |  |  .-.  ||  .___.' |  .___.'|   /  /\_  
|  | \   |  |  |   |  |  |  | |  ||  |      |  |     `-./  /.__) 
`--'  `--'  `--'   `--'  `--' `--'`--'      `--'       `--'

                                            By Pradeep Jairamani

Nmappy performs following Operations:

1: Automating Nmap Scripting Engine Scripts -> nmappy.py -n or nmappy --nse

2: Searching Exploits using Nmap scan results (Uses searchsploit for searching exploits, only works for ubuntu) -> nmappy.py -s or nmappy.py --sploit

3: Finding difference in day-to-day scans and if any difference is found, a mail is send to the user automatically. -> nmappy.py -m or nmappy.py --mail

4: Interactive NMAP scanning -> nmappy.py -i or nmappy.py --interactive

5: Zenmap Default Scans -> nmappy.py -z or nmappy.py --zenmap

6: Directly enter NMAP commands -> nmappy.py -d or nmappy.py --direct

