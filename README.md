![AGPL](https://img.shields.io/github/license/kmahyyg/YNU2GCalendar.svg)
![Python](https://img.shields.io/badge/Python-3.5%2B-blue.svg)

# Disclaimer

This program should **NOT** be used for any illegal purpose. All source code must be used under AGPL-V3.
Your sensitive data will **NOT** be stored in our server after you finished all your operations.
We will not leak any of your data to any third-party service provider.

This program is proudly using Sentry.io Bug Tracker Service. If you chose my software, I recognized you already accepted:
1. [GNU AFFERO GENERAL PUBLIC LICENSE](https://www.gnu.org/licenses/agpl-3.0-standalone.html)
2. Other related Open-source dependencies license
3. [Sentry.io Privacy Policy](https://sentry.io/legal/privacy/1.0.0/)
4. [Sentry.io Privacy Shield](https://www.privacyshield.gov/participant?id=a2zt0000000TNDzAAO)
5. [Sentry.io DPA](https://sentry.io/security/#data-seurity-and-privacy)
6. [Sentry.io Security&Compliance](https://sentry.io/security/#data-seurity-and-privacy)
7. [EU Resident GDPR Protected](https://gdpr-info.eu/)


# YNU2GCalendar with ICS

Use iCalendar format to convert YNU Classes to Google Calendar to make it much more easier for students managing class.

# Ehell System

Because learning is going to more informative. Our school finally decided to selectively migrate to new system.
This system is written by WisEDU Co.,Ltd with an incredibly low-extensible framework and user-unfriendly interface.

# Idea

Thanks to the future of human, Google provided a powerful calendar.
As it always do, cooperating with my Pixel, It provided a useful and efficient notification and GTD system.

Without any connection to the world, you can still use this package.

Using At-A-Glance(R) Feature of Google Pixel Launcher will help you improve your productivity.
The default event notification is Pop-up Notification at 30 minutes before it happened.

# License

Licensed under AGPL V3.0

# Installation and Deployment

Clone this repo to wherever you want first.
Don't forget to modify apikey.py.example first.

**Don't run it in a remote server, running on your local desktop**

> **If you want to have a more detailed support, please don't modify ```sentryid``` in apikey.py.example**

## Client side

```sh
pip install -r ./requirements.txt
cd client_side
cp -a ./chromedriver /usr/bin/
cp ./apikey.py.example ./apikey.py
python3 ./client.py
```

After that, you should copy&paste the ynucal.ics file on your desktop folder to your phone.
Then you can import this file to whichever calendar software you want.

# Issues requirements

LOGCAT OR GTFO!

Provide all of your logs and submit it via Issues. If the file is too large(or you cannot identify which is related one),
please SHARE YOUR LOG via [Pastebin](http://pastebin.ubuntu.com) or [Hastebin](http://hastebin.com).
 
If you don't follow those rules and Issue template, your issue will get **no response and closed directly**.
I will **NOT** receive(also reply) any request via any IM or Email.

#### BTW

Google has a very strong standard applied. While I'm programming for this, It all followed the corresponding international standard.