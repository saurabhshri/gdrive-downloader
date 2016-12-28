# Google Drive File Downloader
Python Script to download any file (any size) from Google Drive.

#Requirements:
1. Python
2. requests module (http://docs.python-requests.org/)
3. Google Drive file's public link.

#Usage
Simply run python file as below : 

```python gdrive_downloader.py```

When prompted, enter the requested details.

#How to get public file ID.

1. Open the Google Drive folder where file is present.
2. On the file you want to download, right click and select "Get Sharable Link". You'll get something like :
``` https://drive.google.com/open?id=0B7xAF1f7vzYzNjFmZXbhdfhgv2 ```
3. Simply copy the part after `id=` _e.g._ `0B7xAF1f7vzYzNjFmZXbhdfhgv2`

