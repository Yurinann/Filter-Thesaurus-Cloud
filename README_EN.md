# Filter-Thesaurus-Cloud

A word-filter thesaurus for minecraft server (via TrChat).
<br>
<br>

**Please do not abuse this thesaurus! Please observe the relevant laws and regulations!**
<br>
<br>

This thesaurus was created to maintain a good communication environment within the Minecraft server. Please do not use or distribute the content of the thesaurus maliciously.

Please use the TrChat plugin with this thesaurus (already built in the plugin).

TrChat (Github): https://github.com/TrPlugins/TrChat
<br>
<br>

Usage (2.0.0+):

`filter.yml`
```yaml
Enable: 
  Chat: true 
  Sign: true 
  Anvil: true 
  Item: false
# Cloud Thesaurus Settings
Cloud-Thesaurus:
  Enabled: true
  Ignored: [] 
  # Cloud Url
  Urls: 
    - 'https://raw.githubusercontent.com/Yurinann/Filter-Thesaurus-Cloud/main/database.json'
Local:
  - 'NMSL'
  - 'fuck'
  - 'shit'
WhiteList: ['has been']
Replacement: '*'
```
Reference Link (Gitbook): https://trchat.plugindoc.cn/an-zhuang-pei-zhi/pei-zhi/guo-lv-qi
<br>
<br>

Usage (1.90-):
```yaml
CLOUD-THESAURUS:
  ENABLE: true
  WHITELIST: []
  # Cloud Url
  URL:
    - 'https://raw.githubusercontent.com/Yurinann/Filter-Thesaurus-Cloud/main/database.json'
```
As above, change CLOUD-THESAURUS.ENABLE to true, add https://raw.githubusercontent.com/Yurinann/Filter-Thesaurus-Cloud/main/database.json (in the same format as above), and restart the server to use this function.

<br>
PR is welcome!

<br>
Note: Most of the content of this thesaurus comes from the Internet and uncivilized language collected in the daily operation of the server.
