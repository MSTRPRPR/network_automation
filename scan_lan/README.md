# scan_lan.py

Scan the local network for any unrecognised hosts and alert using Telegram.

**What it does?**

The script scans the specified address range and collects a list of MAC addresses 
of the hosts that responded to an ARP ping. Then it loops through the list of these 
addresses and compares them with a list of the know MAC addresses you have specified 
in the `vars` file. For any MAC address that is unrecognised, you will get notified 
via Telegram.

**How to:**

1. Create a Telegram bot, create a Telegram chat and add the bot to the chat
2. Store Telegram bot token and chat ID in the `vars` file
3. Update the local network's address and CIDR notation in the `vars` file
4. Update the list of known host MAC addresses in the `vars` file
5. Set up a scheduled job to run this script as often as you would like

