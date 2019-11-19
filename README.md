# CyberPatriots

This repository is to be used to hold notes and scripts for CyberPatriots.

Here is my checklist for Ubuntu. Pretty much everything applies to Windows as well, only the steps to accomplish everything is different.
  1. Read Readme thoroughly and take notes. Anytime you get completely stuck, look at the Readme for hints!
  2. Do the Forensics questions. Any time you don't understand something, Google it. Additionally, the Forensics often give you hints for other issues.
  3. Check all the users in settings. Check that everyone is on the list on the Readme, and delete anyone who isn't. Also check which should be admins and which should be standards. Change everyone's passwords except your own to make them secure.
  4. Enable the firewall. There's a script for this! Also, while you're here, open the firewall gui and look for any suspicious activity in the log.
  5. Install ClamTK to check for malware. Start by running sudo freshclam until it's up to date, then open it up and scan home.
  6. Check for non-professional files such as .mp3s, .wavs, .movs, etcetera. Delete as applicable.
  7. Set auto updates by going to "Software & Updates" > Updates > Automatically Check for Updates. Also check "Install updates from:" and then whatever should be updated. Closing the tab should start up the update process. If not there's a script to check for updates.
  8. Set password policies. There's a script for this! Basically, it sets the minimum length of passwords, the required characters, number of retry attempts, and number of passwords kept in history. 
  9. Set audit policy. 
 10. Disable root login.
 11. Uninstall bad programs. There's a script for this! Checks for telnet, wireshark, nmap, and zenmap, and cleans up any unnecessary packages. Additionally, look for anything else that shouldn't be on the system. Use dpkg --list. Also look in settings for anything out of place.
 12. Disable guest account.
 13. Disable icmp.
 14. Disable ftp.
 15. Enable Firefox popup blocker and set Firefox as default browser.
 16. Remove non admins from admin and sudo groups.
 
  Jesse Bennett
