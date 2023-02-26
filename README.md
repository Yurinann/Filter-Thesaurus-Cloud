# Filter-Thesaurus-Cloud

A word-filter thesaurus for minecraft server (via TrChat).
[EN](README_EN.md)

<br>

*免责声明: 本词库的创建旨在维护 Minecraft 服务器内的良好交流环境。请勿恶意使用或传播词库内容。*

<br>

请使用 TrChat 插件搭配本词库 (插件中已内置) 。
> TrChat (Github): https://github.com/TrPlugins/TrChat

<br>

#

配置参考 (2.0+):

`filter.yml`
```yaml
# 云词库
Cloud-Thesaurus:
  # 是否启用 
  Enabled: true
  # 忽略内容
  Ignored: [] 
  # 第三方词库 （感谢南城提供的词库）
  Urls: 
    - 'https://raw.githubusercontent.com/Yurinann/Filter-Thesaurus-Cloud/main/database.json'
```

参考链接: [Gitbook](https://trchat.plugindoc.cn/an-zhuang-pei-zhi/configs/filter)

<br>

配置参考 (1.90-):

`filter.yml`
```yaml
CLOUD-THESAURUS:
  # 启用
  ENABLE: true
  # 敏感词白名单
  WHITELIST: []
  # 云端词库地址
  URL:
    - 'https://raw.githubusercontent.com/Yurinann/Filter-Thesaurus-Cloud/main/database.json'
```

参考链接: [Gitbook](https://trchat.plugindoc.cn/gui-dang/1.9-documentation/pei-zhi)
#

<br>

欢迎提交 Pull Request！
<br>
注：本词库内容大多来源于网络及在服务器日常运营中收集的不文明语言。
