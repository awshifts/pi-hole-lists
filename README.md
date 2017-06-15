Pi-Hole Lists
=============
This repo was created as an effort to provide users with a "better" adlist with a community-curated whitelist for optimal real-world
usage.

:exclamation: **Please [open a new issue](https://github.com/IAreKyleW00t/pi-hole-lists/issues/new) to recommend changes to any of the
lists, or [create a new pull request](https://github.com/IAreKyleW00t/pi-hole-lists/compare) directly.** :exclamation:

Please see [`adlist.list`](adlist.list), [`whitelist.txt`](whitelist.txt), [`blacklist.txt`](blacklist.txt), and [`wildcards.txt`](wildcards.txt) to see which hosts and
items are specifically included along with an explanation for certain items.

It is **HIGHLY** recommended that you also install [uBlock Origin](https://github.com/gorhill/uBlock), a fast and lightweight adblocker,
on your browser. This will block almost everything that was missed or could not blocked by Pi-Hole as well as help "beautify" webpages.  
[Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en) | 
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) | 
[Edge](https://www.microsoft.com/en-us/store/p/ublock-origin/9nblggh444l4)

---

### Advertisement blocking
Domains known to serve advertisements will be blocked. This will **not** block YouTube ads or ads that are loaded from the same webpage.

### Tracking prevention
Domains known to track user data will be blocked. Unfortunately, some websites/apps require certain domains in order to function
correctly (eg: Spotify, Jackbox.tv, YouTube history, etc.). These are included in [`whitelist.txt`](whitelist.txt) and will be updated
as they are discovered by the community.

### Malicious content blocking
Domains known to have some sort of malicious intent (eg: malware, phishing, exploits, etc.) will be blocked. This is pulled from
multiple sources and takes up the largest number of domains.

### Suspicious domains
Domains with a high level of suspicion will be blocked. These are mainly pulled from a select few number of sources, but are also
curated by the community (see: [`blacklist.txt`](blacklist.txt) and [`wildcards.txt`](wildcards.txt)).

License
=======
```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
