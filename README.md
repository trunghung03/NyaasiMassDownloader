# NyaasiDownloader 

Note: I'm not responsible for bricking your computer.

Change the username accordingly and it will download every torrent or a series of torrents from that user (leaving it at default will download all fakku torrents from user rbot2000). Although from really old Nyaasi torrents with just download links and no magnet links will be ignore.


**Features:**
- Check destination folder to check for duplicates and not download them
- Pass arguments via command line upon executing .py
- More to come


**Guide:**
- Make sure you have bs4 and requests installed
- Run ` $ pip3 install bs4 requests ` if you don't have them
- Get .py file from release
- Pass arguments along with the file in the format below to continue

` $ python3 scraper.py [path] [sukebei] [name] [user]`

path: path to folder to check for duplicates

sukebei: 0 for vanilla nyaasi and 1 for sukebei

name: name of torrent

user: name of torrent uploader

**Example:**

`$ python3 scraper.py ~/Downloads/FAKKU/ 1 fakku rbot2000`
will download every fakku torrent from user rbot2000
