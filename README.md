<h3>Project</h3>
The Open Tor Botnet (ZIB) Official Release<br>
<h3>General information and some instructions.</h3>
You need to use bitcoind.... I will not explain that.<br>
ZIB is fully undetectable and bypasses all antivirus by running on top of Python27's pyinstaller, which is used for many legitimate programs. The only possibility of detection comes from the script, however, the script contains randomized-looking data through using a randomized AES key and initialization vector.<br>
ZIB.py is the main project file. It has 2 errors so nobody who isn't qualified will compile it and do something hazardous.<br>
intel.py is the chat bot.<br>
compileZIB.py is used by intel.py, started with chp.exe to run in the background..<br>
ZIB_imports.txt contains all the imports for ZIB to use. They're appended to the script when compiling.<br>
btcpurchases.txt includes all the bitcoin payments that are pending. Ones older than 24 hours are deleted.<br>
channels.txt includes all completed BTC payments.<br>
You want to point your webserver to dist\ for hosting the files.<br>
chp.exe is required in the local dir.<br>
For the IRC server, run bircd, set up an oper with the username Zlo and password RUSSIA!@#$RUSSIA!@#$RUSSIA!@#$RUSSIA!@#$. For the max users per ip set to 0 because tor users will look like 127.0.0.1Keep all scripts in Python27/Scripts.<br>
Put nircmd in the local directory for editing file dates.<br>
<h3>Credits/Attribution</h3>
Zlo/ZIB/The Open Tor Botnet/Vladimir/DevilsAcid/Alexander<br>
WhitePacket<br>
Python<br>
Socksipy<br>
nircmd<br>
chp<br>
Bitcoin<br>
Pyinstaller<br>
That software was used in the making of this tool. No idea about their licensing so I'm crediting them anyways.<br>
WhitePacket for unleashing the beast.<br>
<h3>Legal</h3>
ZIB is for legal, research purposes only. All of my writings that would be considered illegal if they were not fantasy are entirely fictional.<br>
I won't be held responsible or liable for any damages caused by running this application.<br>
Use this software at your own liability.<br>
Please don't use this for malicious purposes. This was released out of good will and for the benifit of others.<br>
Don't modify/fork/profit off of this project, without proper attribution.<br>
<h3>Features</h3>
ZIB is a IRC-based, Bitcoin-funded bot network that runs under Tor for anonymity.<br>
ZIB is coded totally from scratch and not built on top of someone elses source code.<br>
ZIB uses the Department of Defense standard for encryption of Top Sercret files as one of its methods of making its binaries fully undetectable every time!<br>
ZIB stands for Zlo is a Botnet. Zlo means evil in Russian. (actually ZIB stands for ZIB is a Botnet - a self-referencing acronym)<br>
ZIB creates a new binary for every user, with different file sizes, creation dates, and rot13->zlib->base64->AES-256(random key+IV) encrypted strings.<br>
ZIB is 100% fully undetectable (FUD) to Anti-Virus.<br>
ZIB has an automated system for handling payments, providing bot-net binaries, and creating bot-net IRC channels.<br>
All bot networks on the ZIB network require a password to join.<br>
ZIB uses passworded user-based authentication, handled through our Zlo intel bot, so you don't have to worry about people stealing your channel password, main password, or bots. Normal users can't create their own channels. All IRC functionalities are handled by the Zlo IRC intelligence bot. You can do authenticated, single bot commands through Zlo, or set up a user session on your bots, which is slightly less secure.<br>
Paid users get unlimited bot space per channel.<br>
Our bot has been tested on and is fully compatible with Windows Server 2008 R2 32-bit, Windows XP SP1 & SP3 32-bit, Windows 7, and Windows 8 64-bit. <br>
<h3>Features</h3>
Multi-threaded HTTP/s (hyper-speed layer7 [Methods: TorsHammer, PostIt, Hulk, ApacheKiller, Slowloris, GoldenEye]), TCP/SSL, and fine-tuned UDP flooding. Ability to flood hidden services, or attack via the clearnet. 66 randomized DDoS user-agents and randomized referers from 6 places. All methdos send randomized data, bypass firewalls, filtering, and caching. FTP flood, and TeamSpeak flood.<br>
Undetectable ad-fraud smart viewer [Fully compatible with Firefox, Tor Brwoser Bundle, Portable Firefox, Internet Explorer, Google Chrome, Opera, Yandex, Torch, FlashPeak SlimBrowser, Epic Privacy Browser, Baidu, Maxthon, Comodo IceDragon, and QupZilla].<br>
Download & Execute w/ optional SHA256 verification.<br>
Update w/ optional SHA256 verification.<br>
Chrome password recovery.<br>
Each bot can act as a shell booter and use php shells to hit with.<br>
Replace Bitcoin addresses in clipboard with yours.<br>
FileZilla password recovery.<br>
Fully routed through Tor.<br>
File persistence, registry persistence, startup folder persistence, process persistence, tor process & file persistence.<br>
Completely hidden.<br>
0/60 Fully undetectable to Antivirus.<br>
File download/upload.<br>
Process status, starter, and killer.<br>
Undetectable, instant obfuscation when generating new binaries FREE!<br>
Self spreading.<br>
All bot files are verified via hash check. Broken/corrupted files get re-placed.<br>
Bypasses AntiVirus Deep-Scan.<br>
Bot location changes, depending on administrative access.<br>
IRC nickname fromat: Country[version]windows version|CPU bits|User Privileges|CPU cores|random characters. Ex: US[v2]XP|x32|A|4c|F4L0s4kpN5. 64-bit detection may be having issues (shows up as 32-bit), and will be updated soon.<br>
Disables various windows functions WITHOUT giving the user warnings!<br>
Disables Microsoft Windows error reporting, sending additional data, and error logging - System-wide as administrator, and per-user.<br>
Disables User Access Control (UAC) - System-wide as administrator, and per-user.<br>
Disables Windows Volume Shadow Copy Backup Service (vss) - System-wide as administrator.<br>
Disables System Restore Service (srservice) - System-Wide as administrator.<br>
Disables System Restore - System-Wide as administrator.<br>
100% runs under the Tor anonymity network. No in-proxies like tor2web.org.<br>
Melts on execution. Original file gets deleted. Will likely delete the file out of temporary folder, if used with a binder.<br>
Multi-threaded mass SSH scanner (servers are stored on the bot), no duplicates or honeypots. 4 integrated password lists of increasing difficulty [A,B,C,D], or brute force with min/max characters (does numbers, upper/lowercase letters, symbols). Cracked routers are used for UDP/TCP/HTTP/ICMP flooding. UDP flood requires having the routers download a python script, and the majority of routers won't have Python. Can be used to take down DDoS-protected, or government servers from scanning with just one bot. Can scan under Tor, multiple ports at once, ip range/s [A/B/C] or randomized IPs, optionally block government IPs, blocks reserved IPv4 addresses minus the users LAN.
BotKiller with file scanning [kills .exe, .bat, .scr, .pif, .dll, .lnk, .com] in (AppData, Startup, etc) - Successful against [NanoCore, Andromeda, AGhost Silent Miner, Plasma HTTP/IRC/RAT, almost every HackForums bot.], process scanning (file deletion), and registry scanning.<br>
Mutex. No duplicate IRC connections.<br>
Amazing error handling, install rate, detection ratio, and persistence.<br>
Completely native malware. No .NET framework, or Python installation required!<br>
Installs to the startup folder & AppData (registry start-up).<br>
Kills all popular anti-virus and prevents installation. Can disable Anti-Virus which have rootkits, through deleting important A/V dlls.<br>
BotKiller, scanner, and A/V killer are optional. You can easily run our software as a back-up for your bots, or install other malware on them as back-up. Our service is highly scale-able and isn't going anywhere.
Duel-process and duel-file based persistence. Files are processes are re-created nearly instantly, after being removed.<br>
Steals File-Zilla logins. Great for getting SSH, and FTP logins.<br>
Automatically removes some ad-ware.<br>
Omegle spreader that spreads either a link as a cam show, or a Skype account with every line of text being completely unique to avoid detection. Waits for the user to type a message before responding with a reply. Shows typing and types human-like. Multi-threaded.<br>
Deletes zone identifier on all bot files, Tor, download & executed files, and update files. This means that you don't get the "Would you like to run this program?" dialog, and it runs completely hidden.<br>
Detects all Windows operating systems from Windows 95, ME, to 8. Will show Windows 10 as just Windows, or W8.
Coming soon: GPU detection.<br>
Text-To-Speech (detects if speakers are removed).<br>
Duplicate nick-name handling, ping-out handling, etc.<br>
Tor is downloaded directly from the Tor Project. Only needs to be downloaded once, but still has persistence.<br>
Grab bots IP address, disable/enable bot command response, view status of ssh scanner/omegle spreading/ddos/botkiller and start/stop them.<br>
Kill bot instance, uninstall, grab full OS info, check if a host on a certain port is online/offline (TCP & HTTP check).<br>
Check if a process is running, how many are running, list directories (use \ instead of C:\, e.x !dir \ - Some people run off D:\ drives).<br>
Upload certain files on a bots computer to a FTP server (such as a BTC wallet).<br>
Read files in plain-text off zombie computers. View amount of scanned SSH servers. Kill processes. Bot will tell you about missing command parameters, if a certain parameter is the wrong data-type, etc. Errors from executing a command are outputted to the IRC channel (wont flood).<br>
Commands are ran mutli-threaded and con-currently, for the most part. Your bots wont freeze up every time you run a command.<br>
<h3>Notes</h3>
Yes, everything still links to the original website and IRC channel. (ewww)<br>
The default server won't accept new channels, you have to buy one to host there.<br>
This is probably filled with terrible information, non-commented code, etc... My apologies for this work of "art".<br>
Yes, I wrote the README in 3 minutes without proof-reading. Just releasing ZIB real quick.<br>
<h3>Contact</h3>
Email: whitepacketweb@gmail.com<br>
Jabber: whitepacket@yax.im<br>
Twitter: @WhitePacket<br>
BTC address: 1QASXpprwocj7Y65DghSjjgTXxrUHe6XEN<br>
PGP key:<br>
-----BEGIN PGP PUBLIC KEY BLOCK-----<br>
Version: GnuPG v2<br>
<br>
mQENBFXNfgwBCACtq4nznr/SVM57LSgeXy+DfmdBIkUTi0mCHrY2nI1ekYHHozeW<br>
FCo1yacPx7TzGQ6wILvHvgt8yKi8ke1FAGGA7O2fCCNNJ3j7jibhWI9LSUGNa5DO<br>
Ek3iv4UsDS+QuZq1s+4cDA6E028a17JXW1Vtq/29Oy4f8B6MiBBFfe33pIBP0/az<br>
FZg821A2IvRo1vNDNHMKM/RkOLmGI+bzl55wFp/5r5c80z7d67hZreY99d4WiIPQ<br>
8/rO9tgaJwq1+zciLuLErxgz13mkKbQgbQ79gbd76vcZ+FhqkKK9WstD3Qr2ZHDE<br>
astA8cTcPYv51DZ0Zue3xsvNUsyLrVGn4PNvABEBAAG0JVdoaXRlUGFja2V0IDx3<br>
aGl0ZXBhY2tldEBzaWdhaW50Lm9yZz6JATkEEwEIACMFAlXNfgwCGwMHCwkIBwMC<br>
AQYVCAIJCgsEFgIDAQIeAQIXgAAKCRCyuaK7+vbuLuB+B/9vplRJNzmGx0MPiYX3<br>
AJZiBaQAAimDDbkpz6xN+KjRJqd+z0D/TfT9CE0REscPV4APpxE8kVMUwSgOya+Q<br>
IDzfKu1eONiBhzIB2N7xkc9TGbkbkH9OaRRZEfHmYEFHuLZvXC6ply8a3y1Nsg7c<br>
uxbXlTCCr19Yq9TowvUFjhYcOOLYijo0ew0TReVDVquH1M6od+ijVhuT9ged0aZe<br>
YUOg1whWFjGSToFEu4S0y4SUNo5q0x2Wn18uPQXqnKrDjiQKNsWvZUXMqh6em3RF<br>
3Ga87IMroQYq5lzob4AwMgYKSPCKG1FTz8460xdWO8xQOIfjeIcnT7qJ3dA58dSq<br>
2ftyuQENBFXNfgwBCADsMzQ7X1ZbibgqHzpWf/C0vBce9Arr9Mcz7yGtZqFylw+Q<br>
mWGNRmd5sHVDXu33vDFNYLMsTJZ/7jTnpg8P/GLQC7m1GzB9dq5k0icbax7I8tRX<br>
3Peedrvi91ST7/U2N1xm2AHRbZzdtHB07eWk1/4rcEoHUwxESqtn6FnWMZPKf2+x<br>
8lYWipMRDrgefYTKDeOjntNsvRWqQQ5jIEHYtFBscblvyGjO4iJP2veuRlUUI2uY<br>
Mit9KINsjwIgoJ4v+sUdZAiVZC+sXBYcO9BpXB46tBOedn9ekGeYPvZUW4B+Ae3D<br>
F9GbkFNixgCNtSzxaygYZZUdaF+q445icm0wsIcJABEBAAGJAR8EGAEIAAkFAlXN<br>
fgwCGwwACgkQsrmiu/r27i50+gf/f2iacXu2b+Tz5nJOjq8JHzSOKOU7IE7sjbSZ<br>
IPnRLffMqM3/qc8viZJ2P+YMYgx9t0qz16VjUbtu/kOB0FIQ0aYVWIOGrVAJjTA1<br>
mWsy1buztRQwd9H+DGfIZiciAYi+TCBAuyWt7ZUoiDb4gmqWDAzapbtCJXBvIO2j<br>
7zaZbKhjBuaI42lWhJwPoXnySWRteIs4ii+oAF6+jDnUmY1M8lCr21Ukj9JUhZrM<br>
HoZDP9YN8jXC+25hF3Z34z6jJ8W4VeI5ViL6XmreA8wB9yyjnAxG5WXv1vkhsogB<br>
vXT/kDEIeMeXl+yI8D+nzi3J1BdSn+4Xk3WsWFcv/G/1qc2ynQ==<br>
=++w/<br>
-----END PGP PUBLIC KEY BLOCK-----
