# Filter-Thesaurus-Cloud

A thesaurus for minecraft server (TrChat). 
**请勿滥用、恶意使用本词库！请遵守相关法律法规！ **

这是一个为维护 Minecraft 服务器内交流环境而生的词库。
对于词库内的敏感内容，请勿恶意使用、传播。

推荐您使用 TrChat 搭配本词库达到最好的效果.
(TrChat: https://github.com/FlickerProjects/TrChat)

使用方法:
```
CLOUD-THESAURUS:
  # 启用
  ENABLE: true
  # 敏感词白名单
  WHITELIST: []
  # 云端词库地址
  URL:
    - 'https://raw.githubusercontent.com/Yurinann/Filter-Thesaurus-Cloud/main/database.json'
```
如上，将 CLOUD-THESAURUS.ENABLE 改为 true, CLOUD-THESAURUS.URL 下加入 https://raw.githubusercontent.com/Yurinann/Filter-Thesaurus-Cloud/main/database.json 链接 (格式如上), 重启或输入 /trchat reload (重载不一定生效) 即可使用屏蔽功能.

欢迎提交 Pull Requests, 共同维护网络环境.

注: 如您的网络环境不支持访问 github, 可以使用托管在码云的国内词库, 但不保证词库完善与稳定性 (因部分限制).
https://gitee.com/yurinann/Filter-Thesaurus-Cloud
