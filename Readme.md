# PacktPub Video Downloader (pvdl)

The Easiest way to download any Packt video tutorial

**Notice: You need a Packt account with subscription or free trial to download videos**

## Features

* Download any video using your subscription
* Resume downloads
* Download rate limit
* Easy to use

## How to use

First you need to install the prerequisites. On Debian-based distributions run the following commands:

```bash
sudo apt update
sudo apt install build-essential libcurl4-openssl-dev libssl-dev
```

Clone this repository, install requirements and run the script. For example:

```bash
chmod +x ./pvdl.py
pip install --user -r requirements.txt

./pvdl.py -u username@example.com -p Passw0rd -l "https://subscription.packtpub.com/video/programming/9781788834995"
```

or install pvdl using pip:

```bash
pip install --user pvdl

pvdl -u username@example.com -p Passw0rd -l "https://subscription.packtpub.com/video/programming/9781788834995"
```

Usage:

```bash
usage: pvdl.py [-h] [-u USERNAME] [-p PASSWORD] [-r RATE_LIMIT] [-l LINK]

PacktPub Video Downloader

optional arguments:
  -h, --help            show this help message and exit

required arguments:
  -u USERNAME, --username USERNAME
                        Your Packt Username
  -p PASSWORD, --password PASSWORD
                        Your Password
  -r RATE_LIMIT, --rate-limit RATE_LIMIT
                        Download rate limit
  -l LINK, --link LINK  Packt Video link

```

## License

PacktPub Video Downloader is a free software and is licensed under GNU Public License v3+

For more information see [LICENSE](LICENSE)


## Videos

angular
https://subscription.packtpub.com/video/application_development/9781788998437
https://github.com/PacktPublishing/Angular-8---The-Complete-Guide

react
https://subscription.packtpub.com/video/application_development/9781789132229/

react native
https://subscription.packtpub.com/video/programming/9781789139747
https://github.com/PacktPublishing/React-Native---The-Practical-Guide

nextjs
https://subscription.packtpub.com/video/web_development/9781839210792
https://github.com/PacktPublishing/Universal-React-with-Next.js---The-Ultimate-Guide

mean
https://subscription.packtpub.com/video/application_development/9781789959741
https://github.com/PacktPublishing/Angular-and-Node.js---The-MEAN-Stack-Guide

mern
https://subscription.packtpub.com/video/networking_and_servers/9781789343120

mongo
https://subscription.packtpub.com/video/web_development/9781789954012/
https://github.com/PacktPublishing/MongoDB---The-Complete-Developer-s-Guide-

typescript
https://subscription.packtpub.com/video/programming/9781789951905/
https://github.com/PacktPublishing/Understanding-TypeScript-2020-Edition

nuxtjs
https://subscription.packtpub.com/video/application_development/9781789957396
https://github.com/PacktPublishing/Nuxt.js---Vue.js-on-Steroids

nodejs
https://subscription.packtpub.com/video/web_development/9781838826864
https://github.com/PacktPublishing/NodeJS---The-Complete-Guide
