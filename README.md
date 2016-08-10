# Darkness: Dark Themes for Popular Websites

<img src="" align="left" hspace="10" vspace="10">

**Darkness** is a Chrome extension that provides **dark themes** for popular websites such as Google, Facebook, Gmail and YouTube.

Using dark themes reduces the eye strain and fatigue caused by a bright screen, helps you sleep faster and better at night, and generally makes you awesome :)

<img src="" align="center" hspace="10" vspace="10">

## Features
* Supports 4 websites: Google, Facebook, Gmail, YouTube (help us add more)
* Boasts 3 color schemes: Iceberg, Tomorrow, Material (help us add more)
* Written in Javascript and SCSS (basically CSS with variables)
* Self-hosted. Easy to install on Windows, Mac, Linux
* Available commercially on [Chrome Web Store](https://chrome.google.com/webstore/detail/darkness-beautiful-dark-t/imilbobhamcfahccagbncamhpnbkaenm). Read about the difference.  

## Installation
#####  Installing Darkness Developer Edition:
1. Fork the Darkness repo: https://github.com/liorgrossman/darkness/fork
1. Clone your fork locally: `git clone git@github.com:YourGitHubUsername/darkness.git`
1. `cd darkness`
1. Set up a the original repo as a remote: `git remote add upstream git@github.com:liorgrossman/darkness.git`
1. Get the code: `git fetch upstream`
1. To compile all SCSS files to CSS (required): `npm install`

##### Loading it in Chrome:
1. On Chrome, browse to [chrome://extensions](chrome://extensions)
1. If you have already Darkness installed, disable it
1. Check **Developer mode** in the top of the Extensions page
1. Click **Load unpacked extension...**
1. Choose the directory **darkness-chrome** (same dir as manifest.json)

##### To keep Darkness up-to-date, please pull occasionally:
```bash
git checkout master
git pull upstream master
```

## Contributing Code
Pull requests are welcome!
Please see our [contribution guide](./CONTRIBUTING.MD) to us improve existing skins and create new ones.


## Got more questions?
* Join the [Darkness Developers Community on Facebook](https://www.facebook.com/groups/darkness-developers)
* Contact us at: support@improvver.com


##  License

GPLv3


