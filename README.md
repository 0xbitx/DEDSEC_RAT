> <span style="color: red; font-weight: bold;">⚠️ WARNING:</span> Under development!

<p align="center">
<img src="https://media1.giphy.com/media/7CvPkkkpqkic7J8JMC/200w.webp?cid=ecf05e47nsy9v0zj1k1xjv3xfgpkp9vqjk1pewwixrmx2njr&ep=v1_gifs_related&rid=200w.webp&ct=g", width="300", height="300">
</p>

<h1 align="center"> DEDSEC_RAT </h1>
<h4 align="center"> DEDSEC ADVANCED REMOTE ACCESS TROJAN</h4>
<h4 align="center"> DEDSEC_RAT is a Linux-based REMOTE ACCESS TROJAN for windows and linux.</h4>

### DESCRIPTION

DEDSEC_RAT is a Linux-based tool designed for control and monitoring of compromised systems. It provides functionalities for file management, system monitoring, process control, networking, and more., providing advanced functionality with capable of hiding within a victim's system. It boasts persistence capabilities, ensuring continuous operation.   This tool is intended for penetration testing and ethical hacking purposes only. Ensure you have appropriate permission before using this tool on any device or network.

## Features

### General Commands

  * clear: Clear the previous outputs.
  * cd [directory]: Change directory.
  * ls: List all files in the current directory. -l: Show more information. -s [string]: Search for a file by name. -h: Include hidden files.
  * cat [file]: Read the contents of a file.
  * write "[data]" [filename]: Write data to a file.
  * pwd: Print the current working directory.
  * delete [file/directory]: Delete specified files or directories (e.g., delete file.txt dir1).
  * search [string]: Search for a string in all files.

### Process & System Management

  * proc: List all running processes (proc [string] to search for a specific process).
  * kill [pid]: Kill a process by its PID.
  * env: Show environment variables.
  * sc_list: List all running services.
  * sc_stop [service]: Stop a specific service.
  * user: Display the current user.
  * info: Retrieve full information about the victim's PC.

### File Transfer & Execution

  * download [file]: Download a file from the victim's system.
  * upload [file] [path]: Upload a file to the victim's system (e.g., upload /path/file.py C:\Users\user\Desktop).
  * exec [file]: Send a file from the attacker's PC and execute it on the victim's PC.

### Persistence & Antivirus

  
  * persistence1: Enable persistence via method 1.
  * persistence2: Enable persistence via method 2.
  * av: List all installed antivirus software.

### Password Dumping

  * chrome_pass_dump: Dump all stored passwords in the Chrome browser.
  * wifi_password: Dump passwords of all saved Wi-Fi networks.

### Networking

  * netcon: Show all network connections on the victim's PC.
  * get_mac: Display the MAC address of the victim's PC.
  * firewall_status: Show the firewall status of the victim's PC.
  * open [url]: Open any URL on the victim's PC.

### Clipboard & Keylogging

  * get_clipboard: Get the current clipboard contents.
  * set_clipboard [data]: Set new clipboard contents.
  * keylog: Start a keylogger on the victim's PC.
  * dump_keylog: Dump all logs captured by the keylogger.

### Input Simulation

  * send_keystroke [keys]: Send keystrokes to the victim's PC (e.g., ALTTAB, ALTF4, ENTER, PLAY, PAUSE, etc.).

### System & Power Management

  * powershell [command]: Run a PowerShell command on the victim's PC.
  * start [executable]: Start any executable by name.
  * list_drive: List all drives on the victim's PC.
  * change_passwd [password]: Change the password of any user.
  * hide_file [path]: Hide files in a given path.
  * unhide_file [path]: Unhide files in a given path.
  * display_mode [on|off]: Turn the display on or off.

### Phishing & RDP

  * getpass_phish: Start a phishing attack on the victim's PC to capture passwords.
  * rdp [on|off]: Enable or disable Remote Desktop Protocol (RDP) on the victim's PC.

### Lock & Popup

  * lock: Lock the victim's PC.
  * popup [message]: Display a popup message on the victim's PC. Optionally, specify the number of popups (popup [number] [message]).

### Audio & Webcam

  * vol [0-100]: Set the system volume on the victim's PC.
  * play [path .wav]: Play any audio file on the victim's PC (supports .wav files).
  * webcam_list: List all available webcams on the victim's PC.
  * webcam_shot [webcam_num]: Take a screenshot from the specified webcam.
  * record [seconds]: Start an audio recording on the victim's PC.

### Screen Monitoring & Screenshot

  * screenshot: Capture a screenshot of the victim's screen.
  * watch [start/stop]: Start or stop watching the victim's screen live.

### Chat & Location

  * chatbox: Start a chatbox on the victim's PC.
  * track: Track the location of the victim's PC.

### Visual & Wallpaper Management

  * change_wall [path]: Change the wallpaper on the victim's PC.

### Reboot & IP

  * get_ip: Get the IP address of the victim's PC.
  * reboot: Reboot the victim's PC.

### Blocking Input & Websites

  * block_input: Block the keyboard and mouse on the victim's PC.
  * unblock_input: Unblock the keyboard and mouse on the victim's PC.
  * block_website [website]: Block a specific website on the victim's PC.
  * unblock_website [website]: Unblock a specific website on the victim's PC.

### Miscellaneous

  * speak [message]: Use text-to-speech to speak a message on the victim's PC.
  * bsod: Trigger a Blue Screen of Death (BSoD) on the victim's PC.
  * destroy: Destroy the victim's PC (this command is highly destructive—use with caution).


### INSTALLATION
     git clone https://github.com/0xbitx/DEDSEC_RAT.git
     cd DEDSEC_RAT
     chmod +x dedsec_rat
     sudo ./dedsec_rat

### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu

## Support

If you find my work helpful and want to support me, consider making a donation. Your contribution will help me continue working on open-source projects.

**Bitcoin Address: `36ALguYpTgFF3RztL4h2uFb3cRMzQALAcm`**
   
<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">I'm not responsible for anything you do with this program, so please only use it for good and educational purposes. </h4>

