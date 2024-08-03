# [免责声明Disclaimer](https://github.com/boy86001/SmartProxy-Tools/wiki/%E5%85%8D%E8%B4%A3%E5%A3%B0%E6%98%8EDisclaimer) 
此免责声明适用于 GitHub 上的 "SmartProxy-Tools" 项目，相关链接为 [SmartProxy-Tools](https://github.com/boy86001/SmartProxy-Tools)。

## SmartProxy 白名单

此部分提供了 SmartProxy 插件的白名单配置步骤：

1. **安装插件**：
   - [Chrome 安装链接](https://chromewebstore.google.com/detail/smartproxy/jogcnplbkgkfdakgdenhlpcfhjioidoj)
   - [Firefox 安装链接](https://addons.mozilla.org/en-US/firefox/addon/smartproxy/)

2. **配置白名单**：
   - 打开插件设置，选择「自动切换」-「订阅规则列表」，自行命名。
   - 混淆方式选择「Base64」。
   - 格式选择「AutoProxy/GFWList」。
   - 在 URL 输入框中输入：

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/gfwlist.txt
   ```

   - 点击「保存」-「保存更改」。

## v2rayN/v2rayNG 白名单

此部分介绍了如何为 v2rayN/v2rayNG 配置白名单：

1. **安装工具**：
   - [v2rayN 安装链接](https://github.com/2dust/v2rayN)
   - [v2rayNG 安装链接](https://github.com/2dust/v2rayNG)

2. **配置白名单**：
   - 打开自定义规则设置。
   - 使用逗号 `,` 分隔 URL/IP。
   - 代理的网址或 IP:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/tlURL_Z.xml
   ```

   - 阻止的网址或 IP:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/noURL_Z.xml
   ```

   - 直连的 IP:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/yesIP_Z.xml
   ```

   - 直连的网址:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/yesURL_Z.xml
   ```

## SwitchyOmega 白名单

此部分提供了 SwitchyOmega 插件的白名单配置步骤：

1. **安装插件**：
   - [Chrome 安装链接](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)
   - [Firefox 安装链接](https://addons.mozilla.org/en-US/firefox/addon/switchyomega/)

2. **配置白名单**：
   - 打开插件设置，选择「新增情景模式」-「代理服务器」，自行命名。
   - 选择「新增情景模式」-「自动切换」，自行命名。
   - 将规则列表设置为直连。
   - 默认情景模式设置为刚才创建的代理服务器模式。
   - 添加规则列表，输入以下网址：

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/Switchy_Z.sorl
   ```

   - 点击「立即更新情景模式」，在左上角的「界面」中将初始情景模式改为「自动切换」。

## 致谢

特别感谢以下贡献者：

- [YiSanYuan](https://github.com/boy86001)
- [Loyalsoldier](https://github.com/Loyalsoldier/geoip)