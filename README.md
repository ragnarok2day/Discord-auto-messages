Discord Auto-Messages Bot
Description
This project is a Python script that automates sending messages to specific Discord channels using the Selenium WebDriver. It is designed to work with multiple profiles and channels, allowing for customizable messages and intervals between actions to mimic human behavior and ensure compliance with Discord's usage policies.

Features
Sends predefined messages to Discord channels.
Supports multiple Chrome user profiles.
Randomizes messages and intervals between sending them to add variability.
Easy to customize with your own messages, intervals, and channel URLs.
Requirements
Python 3.x
Selenium WebDriver
Chrome Browser
ChromeDriver
Installation
Install Python 3.x: Make sure Python 3.x is installed on your system. You can download it from the official Python website.

Install Selenium: Run pip install selenium in your terminal to install the Selenium package.

Download ChromeDriver: Download the version of ChromeDriver that matches your Chrome version from the ChromeDriver website. Extract the executable and place it in a known directory or add it to your system's PATH.

Set Up Chrome Profiles: Create or identify Chrome profiles you wish to use with this bot. You will need to provide the paths to these profiles in the script.

Configuration
Profiles: Enter the paths to your Chrome profiles in the profiles list. Example: "/Users/username/Library/Application Support/Google/Chrome/User Data/Profile 1"

Messages: Fill in your predefined messages in the messages list.

Channel URLs: Enter the Discord channel URLs you want to target in the first_channel_url and second_channel_url variables.

Intervals: Adjust the intervals list with your preferred wait times between actions.

Usage
To run the bot, simply execute the script with Python:

sh
Copy code
python discord_auto_messages.py
The script will randomly select a Chrome profile and a message, navigate to the specified Discord channels, and send the messages. It will then wait for a predetermined interval before repeating the process.

Important Notes
Ensure you are logged into Discord on the Chrome profiles you intend to use.
Discord's UI updates may require updating the XPATH used to locate the message input field.
Use this script responsibly to avoid violating Discord's terms of service.
Disclaimer
This project is for educational purposes only. Use it at your own risk. The creator of this bot is not responsible for any consequences that arise from its use, including, but not limited to, account suspension or banning from Discord.
