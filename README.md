[***简休中文 🇨🇳***](README-cn.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[***Русский 🇷🇺***](README-🇷🇺.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[***Disclaimer***](https://github.com/boy86001/SmartProxy-Tools/wiki/%E5%85%8D%E8%B4%A3%E5%A3%B0%E6%98%8EDisclaimer) 

#This disclaimer applies to the "SmartProxy-Tools" project on GitHub (hereinafter referred to as "the project"). The project link is: [SmartProxy-Tools](https://github.com/boy86001/SmartProxy-Tools)

## SmartProxy Whitelist

This section provides instructions for configuring the whitelist for the SmartProxy plugin:

1. **Install the plugin**:
   - [Install for Chrome](https://chromewebstore.google.com/detail/smartproxy/jogcnplbkgkfdakgdenhlpcfhjioidoj)
   - [Install for Firefox](https://addons.mozilla.org/en-US/firefox/addon/smartproxy/)

2. **Configure the whitelist**:
   - In the plugin settings, click "Auto Switch" - "Subscribe Rule List" and set a name of your choice.
   - For obfuscation, select "Base64".
   - For format, select "AutoProxy/GFWList".
   - In the URL input box, enter:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/gfwlist.txt
   ```

   - Click "Save" - "Save Changes".

## v2rayN/v2rayNG Whitelist

This section explains how to configure the whitelist for v2rayN/v2rayNG:

1. **Install the tools**:
   - [Install v2rayN](https://github.com/2dust/v2rayN)
   - [Install v2rayNG](https://github.com/2dust/v2rayNG)

2. **Configure the whitelist**:
   - Open the custom rule settings.
   - Use commas `,` to separate URLs/IPs.
   - For proxy URLs or IPs:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/tlURL_Z.xml
   ```

   - For blocked URLs or IPs:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/noURL_Z.xml
   ```

   - For direct connection IPs:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/yesIP_Z.xml
   ```

   - For direct connection URLs:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/yesURL_Z.xml
   ```

## SwitchyOmega Whitelist

This section provides instructions for configuring the whitelist for the SwitchyOmega plugin:

1. **Install the plugin**:
   - [Install for Chrome](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)
   - [Install for Firefox](https://addons.mozilla.org/en-US/firefox/addon/switchyomega/)

2. **Configure the whitelist**:
   - In the plugin settings, click "Add New Profile" - "Proxy Server" and set a name of your choice.
   - Click "Add New Profile" - "Auto Switch" and set a name of your choice.
   - Set the rule list to direct connection.
   - Set the default profile to the proxy server profile created earlier.
   - Add the rule list by entering the following URL:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/Switchy_Z.sorl
   ```

   - Click "Update Now" in the profile settings and change the initial profile to "Auto Switch" in the top left corner.

## Acknowledgements

Special thanks to:

- [YiSanYuan](https://github.com/boy86001)
- [Loyalsoldier](https://github.com/Loyalsoldier/geoip)

