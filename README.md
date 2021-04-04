<img align="left" width="70px" src="https://raw.githubusercontent.com/QuiteAFancyEmerald/HolyUnblockerPublic/master/views/assets/img/icon.png"></img>
# Holy Unblocker

#### Titanium Network is sponsored by:

<img src="https://raw.githubusercontent.com/QuiteAFancyEmerald/HolyUnblockerPublic/fa858c0e429d73324bffc045bd2a3217064fb1e5/views/assets/img/nodeclusters.png?raw" width="500px"><a href="https://nodeclusters.com"></a></img>

Holy Unblocker, an official flagship Titanium Network site, can bypass web filters regardless of whether it is an extension or network-based. Being a secure web proxy service, it supports numerous sites while being updated frequently and concentrating on detail with design, mechanics, and features.

Works with a large number of sites, including YouTube, Discord, and more! 

Read below for information if the official site is blocked or for obtaining more links.
[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/easella/Holy-Unblocker)

## Usage

#### Supports
- Youtube.com
- Discord.com
- Google.com
- Reddit.com
- Bing.com
- And more!

#### Features:
- Tab customization using the Options menu for improved stealth 
- Considerable variety with the open selection of proxy types 
- Game library with moderately decent titles like A Dark Room 
- Has frequent support articles for issues relating to the various proxy instances

Be sure to join Titanium Network's Discord for more official site links: https://discord.gg/hcUUceSCtj

Do %proxy hu for more Holy Unblocker links on the Titanium Network Discord server.

**Official Site:** https://www.holyubofficial.net

**Site Documentation:** Documentation

<img src="https://raw.githubusercontent.com/QuiteAFancyEmerald/HolyUnblockerPublic/master/views/assets/img/hbpreview.png?raw"></img>

<a href="https://heroku.com/deploy?template=https://github.com/QuiteAFancyEmerald/HolyUnblockerPublic" title="Deploy to Heroku"><img alt="Deploy to Heroku" src="https://raw.githubusercontent.com/QuiteAFancyEmerald/HolyUnblockerPublic/master/views/assets/img/heroku.svg?raw" width="140" height="30"><img></a>
&nbsp;
<a href="https://azuredeploy.net/" title="Deploy to Azure"><img alt="Deploy to Azure" src="https://raw.githubusercontent.com/QuiteAFancyEmerald/HolyUnblockerPublic/master/views/assets/img/azure.svg?raw" width="140" height="30"><img></a>
&nbsp;
<a href="https://repl.it/github/QuiteAFancyEmerald/HolyUnblockerPublic" title="Run on Repl.it"><img alt="Run on Repl.it" src="https://raw.githubusercontent.com/QuiteAFancyEmerald/HolyUnblockerPublic/master/views/assets/img/replit.svg?raw" width="140" height="30"><img></a>
&nbsp;
<a href="https://glitch.com/edit/#!/import/github/QuiteAFancyEmerald/HolyUnblockerPublic" title="Remix on Glitch"><img alt="Remix on glitch" src="https://raw.githubusercontent.com/QuiteAFancyEmerald/HolyUnblockerPublic/master/views/assets/img/glitch.svg?raw" width="140" height="30"><img></a>
         
## Table of contents:

- [Setup](#how-to-install)
	- [Structure](#structure)
		- [Structure Information](#structure)
	    - [Static Files](#details-of-views)
	    - [Proxy Scripts](#scripts-located-in-expr)
	- [Future Additions](#future-additions)
	- [Beginner's Explanation](#vauge-explanation-for-beginners-with-external-proxies-and-hosting)
	  - [Hosting Providers](#list-of-some-good-hosting-options)
	  - [Heroku Setup](#heroku-steps)
	  - [Domain Setup](#freenomdomain-steps)
	  - [Cloudflare Setup](#cloudflare-steps)
	  - [Workspace Configurations](#workspace-configurations)
	- [Detailed FAQ](#detailed-faq)
	- [More Information](#more-information)

## How to Setup
Either use the button above to deploy to Heroku or do the below:
```
$ git clone https://github.com/QuiteAFancyEmerald/HolyUnblockerPublic.git
$ cd HolyUnblockerPublic
$ npm install
```
Afterward, run:
```
$ npm start
```
For more detailed documentation on workspace setup, please view <a href="https://holyubofficial.net/?faq">this</a>.

The default place for the proxy when it started is `http://localhost:8080`, but it can be changed if needed in config.json

This website has been hosted locally on Alloy Proxy. For more information, head over to the Alloy Proxy repository below.

## Structure
- `index.html`: The official homepage of the site.
- `surf.html`: Web Proxies page, the page offers to be redirected to any proxies you would like to add. In this case, Alloy, Womginx, Powermouse, and Via Unblocker.
- `alloy.html`: Official Alloy Proxy page, which features Alloy hosted locally but can be configured to redirect to an external instance.
- `womginx.html`: Womginx Proxy page. Script links to a subdomain for Womginx, a highly fast proxy with captcha support.
- `pmprox.html`: SysYA Proxy page. Script links to a subdomain for SysYA Proxy, a flexible secondary proxy compared to Alloy with Discord support.
- `pydodge.html`: Via Unblocker page. Links to a subdomain with PyDodge or Via, a proxy which successes Node Unblocker
- `youtube.html`: An proxied version of Youtube running off of the locally hosted Alloy Proxy.
- `discordhub.html`: Hub for the Discord proxy and its links using a mixture of Alloy and Womginx.
- `gtools.html`: Games page, help from @BinBashBanana and @kinglalu.
- `flash.html`: Games page for flash games, credits are given to @BinBashBanana and Titanium Network for its assets.
- `emulators.html`: Emulator navigation page, hosted locally on Holy Unblocker.
- `bookmarklets.html`: Bookmarklets page to be worked on more in the future.
- `icons.html`: Information regarding Options Menu. 
- `info.html`: Official Documentation page.
- `terms.html`: Terms of Services, AUP, and Privacy Policy page.
## Deprecated
Left all of these just if you would like to set up the site differently as surf.js can be used instead.
- `ythub.html`: Page linking proxied Youtube.
- `ytmobile.html`: Page linking to a proxied YouTube for mobile users
- `discordprox.html`: Links to a discord proxied through Alloy.
- `gba.html`: Locally hosted Gameboy Emulator.
- `chatbox.html`: Links to an externally hosted Chatbox.
- `krunker.html`: An iframe version of Krunker with keyword changes. It can be removed if not needed.
### Structure Information
- `/views/`: The physical site base of Holy Unblocker goes here where static assets are served.
- `/src/`: For future implementation of obfuscation and keyword removing features.
#### Details of /views/
- `/pages/` is used for important pages for the site.
- `/expr/` is used for important proxy scripts.
- `/archive/` is used for game related assets and pages.
- `/assets/` is used for various assets for CSS, JS and Bootstrap.
- `/vibeOS/` is used for vibeOS, an in-browser OS enviroment.
#### Scripts located in /expr
- `surf.js` is used for proxy navigation, both Stealth mode and Classic mode.
- `h5-nav.js` is used for navigation on the games page, Stealth mode only.
- `surf-dev.js` is used for proxy navigation on the official sites.
## Future Additions
- Expand the game library
- Go through various parity changes.
- Clean up the source a bit
A- dd more locally hosted proxies possibly.
## An explanation for Beginners With External Proxies and Hosting
You will first want to host your proxies locally or externally. Note that an older version of Alloy proxy is the only proxy hosted locally with this distribution of Holy Unblocker.

**Proxies that you will need for a complete setup for Holy Unblocker:**

Womginx - https://github.com/binary-person/womginx

SysYA Proxy - https://github.com/sysce/proxy

Via Unblocker/PyDodge -https://github.com/BinBashBanana/PyDodge

Alloy Proxy - https://github.com/titaniumnetwork-dev/alloy

The source used for Via Unblocker on the official sites is not public.

**List of some good hosting options:**

- Dedipath (Paid and Dedicated)
- Heroku (Free)
- NodeClusters (Paid)
- Glitch (Free)
- Repl.it (Free)
- Azure (Free and Paid)
- 
Out of the list of hosting providers Heroku and Dedipath rank first as a preference. 

You may also self-host. Currently, at this time, Dedipath is used to host the official Holy Unblocker sites.

After you have selected a decent VPS, use Cloudflare for DNS records for both the site and the subdomains for the proxies.
The image below is an example of DNS records involving Heroku. Self-hosting will require A records, preferably. 

<img src="https://cdn.discordapp.com/attachments/681203088862085168/820048397662158858/unknown.png" width="500"></img>

**The configuration being used on the official sites currently are the below:**

- `a.example.com` is used for Womginx.
- `c.example.com` is used for SysYA Proxy, Via Unblocker, and the Chatbox.
- `cdn.example.com` is used for a private, updated Alloy instance.
### Heroku Steps
So use Heroku to host. I favor it as a free choice.

- First, obtain a card; (Prepaid, Debit, and Credit Cards work). It would be best if you had this to add custom domains to your Heroku instance.
- Make sure you connect your Heroku app to your GitHub and enable automatic deploys. It will make things easier. :)

### Freenom/Domain Steps
For beginners, Freenom is a good provider for obtaining domains for free. However, the catch is that you can only use properly "Freenom" domains for free, being .cf, .ml, .gq, ga, and .tk. However, these can be blocked relatively easily.

- Get some Freenom domains, then add them to your Heroku instance (Personal > [App Name] > Settings > Domains). 
- Add a domain for both www.youdomainhere.cf and yourdomainhere.cf with .cf being interchangeable with other Freedom domain names.

If you prefer to obtain premium domains (TLDs), then use Porkbun, which offers domains for excellent prices. A .net domain typically costs around $10. On Porkbun for the first year, it costs $3, so it is a deal.

### Cloudflare Steps
Use Cloudflare (make an account), add your site (Freenom Domain or Domain), and then add your various DNS targets to Cloudflare. Make sure you add Cloudflare's Nameservers which will be specified more when you are adding your site.

Lastly, for targets, make sure they are either a CNAME, AAAA, or A records and try to follow this structure:

Type | Name | Target

`CNAME | @ | yourherokudnstargethere.herokudns.com` or `CNAME | @ | example.com`

`CNAME | www | yourherokutargethere.herokudns.com` or `CNAME | www | example.com`

Below are if you want external proxies also with your site:

`CNAME | a | yourwomginxinstance.herokudns.com` or `CNAME | a | example.com`
`CNAME | c | yoursysyaproxyinstancehere.herokudns.com` or `CNAME | c | example.com`

(You get the idea.)

Make sure HTTPS is forced and have SSL set to Flexible for Heroku. Otherwise, you may have SSL set to Full. Use LetsEncrypt for SSL certificates or Cloudflare.

## Workspace Configurations
Preferably use Visual Studio Code for an IDE. Pretty much the best option you can get, but obviously, this is an opinion. Also, make sure you have Node.JS installed on your machine.

Not going to go too in-depth with this part but first, fork or clone this repository. Clone it locally through a terminal of some sort, depending on what OS you are on.

Make sure you navigate to the folder you want to set this up in.
```
$ git clone https://github.com/QuiteAFancyEmerald/HolyUnblockerPublic.git
$ cd HolyUnblockerPublic
$ npm install
```
Setup pm2 (Optional - Node.js Process Manager)
```
$ npm install pm2@latest -g
$ pm2 start app.js
```
Useful pm2 Flags
```
# Specify an app name
--name <app_name>

# Watch and Restart app when files change
--watch

# Set memory threshold for app reload
--max-memory-restart <200MB>
```
For more information, view the official pm2 documentation here.

#### Workspace Setup (continued)
Now add the folder you cloned in VSC. Then run npm install. It is recommended that if you are releasing this publically on GitHub that you add a .gitignore in your root directory with the following exclusions:

`node_modules`

Now you have your following workspace environment setup. To deploy the following workspace you just created, you will need to lookup depending on your hosting provider.

- For an online IDE that you can use on your school computer or Chromebook, use GitPod. The equivalent of Visual Studio Code but with in-browser support.
- Make an account: https://gitpod.io/.
- Fork this repo and enter in this URL to set up your workspace: `https://gitpod.io#https://github.com/YourNameHere/HolyUnblockerPublic/`

Use the same steps above by running npm install in your repository and adding a .gitignore in your root directory specifying to exclude `node_modules`.

## Detailed FAQ
A detailed FAQ with common issues and solutions can be found here or on any official HU site on the FAQ page.
**
Why are YouTube videos not working?**

If you have persistent issues even after doing the steps above, the instance is down temporarily, especially if large groups of people are also having the issue. The latest release of Alloy currently does not have support for YouTube. However, manually putting in full links like `https://www.youtube.com/watch?v=mauV2NdCs60` will work. You may also try doing a Hard Reload (Ctrl+Shift+R)
A later release of Alloy may fix this issue. Sorry.

**Why is the site I am on not working correctly or having CAPTCHA errors?**

Captcha has limited support on Womginx. However, support is not available on some of the older proxies, sadly. Therefore some sites may not work with any of the sites. Read below for issues with links on sites.

**Why are page links not working or leading to 404 pages?**

This is an issue with Alloy proxy's latest release, but it may also occur with other proxies. In this case, manually entering the URL of the page you would like to view can solve this, or try navigating using the home button. (Reddit, Twitter) The next release of Alloy may fix this also.

**When using YouTube on any of the proxy sites, why does the page not load entirely, or the video just white?**

There are two methods for fixing this:
- Reloading the page usually when the error above happens should load the video.
- Alternatively, right-clicking the page and doing Reload Frame if you are using some form of Stealth Mode may work.

**When using Discord under Alloy or Powermouse, why does the page stay gray/white, or the QR code not loading? **

Womginx now supports logging in, usually for Discord. However, here are the steps related to Alloy troubleshooting.
Note that this is for the older discord proxy steps with Alloy and SysYA Proxy.

**On the official sites, I am getting 502 errors. What do I do?**

The proxy may be down, being worked on, or is under high load.
When this happens, you may either switch sites to fix the error or wait a bit. Sometimes clearing your cache can help by doing Ctrl+Shift+R or reloading the page usually. (Hard Reload, which purges cache.)

##More Information
This project is maintained by Quite A Fancy Emerald and is an official flagship Titanium Network proxy site.

- https://titaniumnetwork.org/
- https://github.com/titaniumnetwork-dev/
- 
View the official website for more details or credits.

### Proxy Sources:
This project uses Alloy Proxy, Womginx, SysYA Proxy, and Via Unblocker, linked below.

- https://github.com/titaniumnetwork-dev/alloy (Alloy)*
- https://github.com/binary-person/womginx (Womginx)
- https://github.com/sysce/proxy (SysYA Proxy)
- https://github.com/hypothesis/via (Via)**
- https://github.com/BinBashBanana/PyDodge (PyDodge)**
- https://github.com/nfriedly/node-unblocker (Node Unblocker)***

### Notable Mentions:
- https://dedipath.com (Hosting Provider)

### Footnotes:
- This distribution of Holy Unblocker uses an older version of Alloy Proxy.
- The official Holy Unblocker sites use a private, modified version of Via and goes under the name PyDodge for any modified version.
- Node Unblocker is no longer used on any of the official Titanium Network flagship sites.

Thanks. :D
