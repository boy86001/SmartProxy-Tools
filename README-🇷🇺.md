[***Русский 🇷🇺***](README-🇷🇺.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

# [Отказ от ответственности](https://github.com/boy86001/SmartProxy-Tools/wiki/%E5%85%8D%E8%B4%A3%E5%A3%B0%E6%98%8EDisclaimer)
Этот отказ от ответственности применяется к проекту "SmartProxy-Tools" на GitHub. Ссылка на проект: [SmartProxy-Tools](https://github.com/boy86001/SmartProxy-Tools).

## Белый список SmartProxy

В этом разделе приведены шаги для настройки белого списка для плагина SmartProxy:

1. **Установите плагин**:
   - [Ссылка на установку для Chrome](https://chromewebstore.google.com/detail/smartproxy/jogcnplbkgkfdakgdenhlpcfhjioidoj)
   - [Ссылка на установку для Firefox](https://addons.mozilla.org/en-US/firefox/addon/smartproxy/)

2. **Настройка белого списка**:
   - Откройте настройки плагина, выберите «Автоматическое переключение» - «Список правил подписки» и дайте имя.
   - Выберите «Base64» для маскировки.
   - Выберите формат «AutoProxy/GFWList».
   - В поле URL введите:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/gfwlist.txt
   ```

   - Нажмите «Сохранить» - «Сохранить изменения».

## Белый список v2rayN/v2rayNG

В этом разделе объясняется, как настроить белый список для v2rayN/v2rayNG:

1. **Установите инструменты**:
   - [Ссылка на установку v2rayN](https://github.com/2dust/v2rayN)
   - [Ссылка на установку v2rayNG](https://github.com/2dust/v2rayNG)

2. **Настройка белого списка**:
   - Откройте настройки пользовательских правил.
   - Используйте запятую `,` для разделения URL/IP.
   - Для прокси URL или IP:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/tlURL_Z.xml
   ```

   - Для заблокированных URL или IP:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/noURL_Z.xml
   ```

   - Для IP с прямым подключением:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/yesIP_Z.xml
   ```

   - Для URL с прямым подключением:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/yesURL_Z.xml
   ```

## Белый список SwitchyOmega

В этом разделе приведены шаги для настройки белого списка для плагина SwitchyOmega:

1. **Установите плагин**:
   - [Ссылка на установку для Chrome](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)
   - [Ссылка на установку для Firefox](https://addons.mozilla.org/en-US/firefox/addon/switchyomega/)

2. **Настройка белого списка**:
   - Откройте настройки плагина, выберите «Добавить новый профиль» - «Прокси-сервер» и дайте имя.
   - Выберите «Добавить новый профиль» - «Автоматическое переключение» и дайте имя.
   - Установите список правил на прямое подключение.
   - Установите профиль по умолчанию на созданный ранее профиль прокси-сервера.
   - Добавьте список правил и введите следующий URL:

   ```bash
   https://raw.githubusercontent.com/boy86001/SmartProxy-Tools/main/Switchy_Z.sorl
   ```

   - Нажмите «Обновить сейчас», а в верхнем левом углу интерфейса измените начальный профиль на «Автоматическое переключение».

## Благодарности

Особая благодарность следующим участникам:

- [YiSanYuan](https://github.com/boy86001)
- [Loyalsoldier](https://github.com/Loyalsoldier/geoip)