# Skillshare course downloader for offline viewing (for VFXmed community)
This is used to download skillshare courses for offline viewing if you want to watch courses underway without wasting mobile data.
Premium Account(or trial account) needed.
For educational/and or legitimate purposes only!

**The videos will be downloaded into the same directory you are running the script from and will be sorted into folders for each course**

## Step 1: Setting up and installing requirements
- Open cmd in Windows as administrator (search for cmd, then right-click and hit "run as administrator").
- Navigate to your folder with the ```requirements.txt``` in it by typing ```cd /pathtofolder/skillshare-offline-use```
- Then download and install requirements for python module by typing ```pip install -r requirements.txt```

## Step 2: Getting Course Cookies
- Go to: https://www.skillshare.com/ and navigate to the page of the course you want to download.
- Use a cookie manager like <a href="https://microsoftedge.microsoft.com/addons/detail/cookie-editor/ajfboaconbpkglpfanbmlfgojgndmhmc?hl=de" target="_blank">Cookie Editor</a> to get and copy the PHPSESSID value of the website cookie
- Paste copied value into cookie.txt after ```PHPSESSID=```

## Step 3: Download the Course
Run ```python downloader.py``` in cmd, enter the URL of your course when prompted and select subtitle features.

![Downloader](https://user-images.githubusercontent.com/45739297/158018672-ea92062c-1a63-4a8d-ba9a-7fd14439c7cb.JPG)



**NOTE: It is _highly_ recommended to run this using PyCharm or other IDE applications, as it runs more reliably than in cmd.**

Credits for original skillshare python module: @kalqvist
