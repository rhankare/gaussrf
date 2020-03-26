# gaussrf
```


____________________  __   ________________________________
__  ____/__    |_  / / /   __  ___/_  ___/__  __ \__  ____/
_  / __ __  /| |  / / /    _____ \_____ \__  /_/ /_  /_    
/ /_/ / _  ___ / /_/ /     ____/ /____/ /_  _, _/_  __/    
\____/  /_/  |_\____/      /____/ /____/ /_/ |_| /_/       
                                                           


```
Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl and Filter Urls With OpenRedirection or SSRF Parameters.

## Prerequisites

* [GetAllUrls](https://github.com/lc/gau) - For Fetching Urls
* [Assetfinder](https://github.com/tomnomnom/assetfinder) - For Subdomain Enumeration
* [Anti-burl](https://github.com/tomnomnom/hacks/tree/master/anti-burl) - For check if url is live or not.

### Installation

```bash
$ git clone https://github.com/KathanP19/gaussrf.git
$ cd gaussrf/
$ sudo chmod +x ssrf.sh
``` 
### Usage

```bash
$ ./ssrf domain.com

```

## Credits:
Thanks @tomnomom for [Assetfinder,Anti-burl](https://github.com/tomnomnom)!
Thanks @lc for [GAU](https://github.com/lc/gau)!