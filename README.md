# 5000-Auto-YouTube-Comments-Using-Localhost
5000 Auto YouTube Comments Using Selenium with Python on Localhost

𝙉𝙤𝙩𝙚:𝘿𝙞𝙙𝙣'𝙩 𝙘𝙤𝙥𝙮-𝙥𝙖𝙨𝙩𝙚 𝙘𝙤𝙙𝙚 𝙖𝙜𝙖𝙞𝙣 𝙖𝙣𝙙 𝙖𝙜𝙖𝙞𝙣 𝙎𝙤𝙢𝙚 𝘾𝙝𝙖𝙣𝙜𝙚𝙨 𝘼𝙧𝙚 𝙏𝙝𝙚𝙧𝙚.

## "If you know proxy rotation, then please fork it".

https://www.youtube.com/watch?v=FVumnHy5Tzo&t=1s&ab_channel=HelloWorld

## 𝙬𝙖𝙩𝙘𝙝 𝙪𝙥𝙩𝙤 3mins.46sec+ 𝙩𝙝𝙚𝙣 𝙧𝙚𝙢𝙖𝙞𝙣𝙞𝙣𝙜 code in the script

First, open Chrome file location and bypass the location restriction using an extension such as Touch VPN. In my case, the Chrome location(use start in: path) is

C:\Users\Hp\AppData\Local\Google\Chrome\Application

click window button and search cmd and enter

cd C:\Users\Hp\AppData\Local\Google\Chrome\Application (1st line in cmd)

in line enter

chrome.exe --remote-debugging-port=9222 --user-data-dir=""(in "enter your localhost path here")

Next, enter this command into the terminal, replacing "enter your localhost path here" with your localhost path:

For example, in my case it is:

chrome.exe --remote-debugging-port=9222 --user-data-dir="C:\Users\Hp\Desktop\Bots\Chromedriver\Localhost" (2nd line in cmd make sure you replace the localhost path)

# then again open new terminal in that folder enter

pip install selenium==4.2.0

for yt video 

enter video.py or double click on video.py

for shorts video

enter shorts.py or double click on shorts.py

In lines 11 and 12 of the code, change the comments if you want to use something different.

In line 21, change the movie video URL to the required URL.

press control + f and enter 50 and replace with how much cmts needed for each acc..

That's it! The URL will open in the previously opened localhost Chrome and 5000+ auto comments will be done automatically.

# 👉Note:-

👉if your selenium version is in latest version then the code never run

👉open cmd and enter pip uninstall selenium

And enter

pip install selenium==4.2.0

and hit enter

and

python -c "import selenium; print(selenium.version)"


𝙏𝙝𝙞𝙨 𝙞𝙣𝙛𝙤𝙧𝙢𝙖𝙩𝙞𝙤𝙣 𝙞𝙨 𝙤𝙣𝙡𝙮 𝙛𝙤𝙧 𝙚𝙙𝙪𝙘𝙖𝙩𝙞𝙤𝙣al 𝙥𝙪𝙧𝙥𝙤𝙨𝙚 𝙖𝙣𝙙 𝙬𝙚 𝙖𝙧𝙚 𝙣𝙤𝙩 𝙧𝙚𝙨𝙥𝙤𝙣𝙨𝙞𝙗𝙡𝙚 𝙛𝙤𝙧 𝙖𝙣𝙮 𝙠𝙞𝙣𝙙 𝙤𝙛 𝙞𝙡𝙡𝙚𝙜𝙖𝙡 𝙖𝙘𝙩𝙞𝙫𝙞𝙩𝙮 𝙙𝙤𝙣𝙚 𝙗𝙮 𝙩𝙝𝙞𝙨 𝙩𝙤𝙤𝙡.
