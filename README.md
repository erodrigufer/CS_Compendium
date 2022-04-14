# CS Compendium
A centralized personal compendium of computer science resources.

# Table of contents
<!-- vim-markdown-toc GFM -->

* [Software engineering](#software-engineering)
	- [Design patterns](#design-patterns)
	- [Developer productivity](#developer-productivity)
	- [Git](#git)
	- [Regex](#regex)
* [Web development](#web-development)
	- [HTML](#html)
	- [HTTP(S)](#https)
	- [Security](#security)
* [Design](#design)
	- [UI](#ui)
* [FreeBSD sysadmin](#freebsd-sysadmin)
	- [Daemons](#daemons)
	- [Monitoring](#monitoring)
	- [Networking](#networking)
	- [SSH](#ssh)
	- [Databases](#databases)
* [General sysadmin](#general-sysadmin)
	- [Networking](#networking-1)
	- [Containers](#containers)
	- [OS](#os)
* [Unix](#unix)
* [Observability](#observability)
* [Concurrency](#concurrency)
* [Databases](#databases-1)
	- [SQL](#sql)
* [SaaS/Business](#saasbusiness)
	- [Pricing](#pricing)
* [Security](#security-1)
	- [Malware](#malware)
* [Academia](#academia)

<!-- vim-markdown-toc -->
## Software engineering
### Design patterns
* [Why is Global State so Evil?](https://softwareengineering.stackexchange.com/questions/148108/why-is-global-state-so-evil): A discussion with in-depth argumentation against writing code/functions that depend on _global state_. 

### Developer productivity
* [Fire and motion](https://www.joelonsoftware.com/2002/01/06/fire-and-motion/): The struggle with developer productivity in a nutshell. [_Joel Spolsky_]

### Git
* [Fortunately I don't squash my git commits](https://blog.ploeh.dk/2020/10/05/fortunately-i-dont-squash-my-commits/): A long bug hunting journey as a testament to not squashing commits. [_Mark Seemann_]

### Regex
* [Regex cheatsheet](https://paul.copplest.one/knowledge/tech/regex.html): Paul Copplestone's **regex cheatsheet** [_Paul Copplestone_]

## Web development
### HTML
* [HTML cheatsheet](https://paul.copplest.one/knowledge/tech/html-cheatsheet.html): Paul Copplestone's HTML cheatsheet [_Paul Copplestone_]

### HTTP(S)
* [Conditional HTTP GET: The fastest requests need no response body](https://ieftimov.com/post/conditional-http-get-fastest-requests-need-no-response-body/): Handling server content update with ETags and Last-Modified _header fields_ in order to generate user-agent content caching [_Ilija Eftimov_]
* [Decrypting your own HTTPS traffic with Wireshark](https://www.trickster.dev/post/decrypting-your-own-https-traffic-with-wireshark/): Properly configuring Wireshark with the keys to decrypt local HTTPS traffic fow debugging and hacking
### Security
* [Do login forms need tokens against CSRF attacks?](https://stackoverflow.com/questions/6412813/do-login-forms-need-tokens-against-csrf-attacks): From StackOverflow, is it necessary to protect login forms against CSRF (Cross-site request forgery) attacks?

## Design
### UI
* [Why Japanese web design is so... different](https://randomwire.com/why-japanese-web-design-is-so-different/): An explanation about the cultural differences and the socio-technological context that makes some big Japanese web sites feel so different, like if they stayed behind within the web design paradigms of the 90s.

## FreeBSD sysadmin
### Daemons
* [Supervised FreeBSD rc.d script for a Go daemon](https://redbyte.eu/en/blog/supervised-freebsd-init-script-for-go-deamon/): Run a go program as a supervised daemon in FreeBSD.
### Monitoring
* [FreeBSD Install Logwatch Tool For Log Analysis and Monitoring](https://www.cyberciti.biz/faq/freebsd-unix-log-analyzer-configuration/): Tutorial on how to install and setup _Logwatch_ to get daily logs' analysis through emails.

### Networking
* [Check open ports on FreeBSD](https://linuxhint.com/check-open-ports-freebsd/): _sockstat_ command

### SSH
* [How to configure ssh key authentication on FreeBSD](https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-freebsd-server)

### Databases
* [How to install MariaDB on FreeBSD](https://www.osradar.com/how-to-install-mariadb-on-freebsd-12/)

## General sysadmin
* [Cron best practices](https://blog.sanctum.geek.nz/cron-best-practices/): Best practices to manage and setup cronjobs in a secure way, e.g. periodically monitoring a web service with a cron job.
* [Land chad's guide to setting up a webserver](https://landchad.net/domain): Step by step guide by Luke Smith on how to setup a server, its domain, firewall, etc... [_Luke Smith_]

### Networking
* [Using UFW as a Firewall](https://landchad.net/ufw): Very minimalistic/simple guide to configure UFW on a server. [_Luke Smith_]

### Containers
* [Docker cheatsheet](https://paul.copplest.one/knowledge/tech/docker.html): Docker cheatsheet [_Paul Copplestone_]

### OS
* [Choosing between FreeBSD and OpenBSD](https://unixsheikh.com/articles/choosing-between-openbsd-and-freebsd.html): Reasoning behind choosing between FreeBSD or OpenBSD [_Unix Sheikh_]

## Unix
* [A list of new(ish) command line tools](https://jvns.ca/blog/2022/04/12/a-list-of-new-ish--command-line-tools/): A list of _modern_ Unix command line tools, to improve on classic Unix command line tools. [_Julia Evans_]

## Observability
* [Logging v. instrumentation](https://peter.bourgon.org/blog/2016/02/07/logging-v-instrumentation.html): Difference between logging and instrumentation, best practices for both. [_Peter Bourgon_]

## Concurrency
* [Scheduling In Go : Part I - OS Scheduler](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part1.html): Description of how an OS scheduler works with multiple threads and the performance challenges faced by a multi-threaded program. [_William Kennedy_]

## Databases
* [How does database indexing work?](https://stackoverflow.com/questions/1108/how-does-database-indexing-work): Stackoverflow discussion about how database indexing works and why it is useful. It provides other links to other threads discussing the same topic.
* [PostgreSQL cheatsheet](https://paul.copplest.one/knowledge/tech/postgresql.html): PostgreSQL cheatsheet [_Paul Copplestone_]

### SQL
* [Animate SQL](https://animatesql.com/): Animated web resource to better the functionality of SQL commands in a graphical way.

## SaaS/Business
### Pricing
* [Pricing low touch SaaS](https://stripe.com/en-gb-de/atlas/guides/saas-pricing)
* [Profit sharing](https://paul.copplest.one/blog/profit-sharing.html): A rather unorthodox approach to profit sharing in a private company. [_Paul Copplestone_]

## Security
### Malware
* [Malware targetting AWS Lambda](https://www.cadosecurity.com/cado-discovers-denonia-the-first-malware-specifically-targeting-lambda/): A malware written in Go that targets AWS Lambda functions.

## Academia
* [You should be reading academic CS papers](https://stackoverflow.blog/2022/04/07/you-should-be-reading-academic-computer-science-papers/): A Stackoverflow blog post recommending resources to get access to good academic computer science papers. [_Stackoverflow Blog_]
