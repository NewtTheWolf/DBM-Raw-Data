# Umfrangreiches Logging System

Big Brother is Watching You ! Mit diesem Log System könnt ihr alles mögliche auf eurem Discord Server Protokollieren.
Folgendes Log Methoden stehen euch zur Verfügung

- Gelöschte Nachtichten Protokollierung
- Editierte Nachrichten Protokollierung
- Editierte Usernamen Protokollierung
- User Erwähnung Protokollierung 
- Bot Error Protokollierung

Für alle RAW DATA´s bennötigt ihr die Aktuellen **[DBM Mods](https://github.com/Discord-Bot-Maker-Mods/DBM-Mods)** und die **DBM Beta Steam Version**

# Gelöschte Nachrichten LOG (UPDATE 12.07.2019)
Diese RAW Data müsst ihr zu euren **Events** packen.

**Zu Beachten:**
- **ACTION #6** gebe dort deine **Channel ID** ein wo es geloggt werden soll.
- **ACTION #8** gebt hier euren **Bot Prefix** ein. (Standard ist es auf **!** eingestellt, daher nur ändern wenn ihr einen anderen Prefix als ! verwendet)

![github-large](https://i.imgur.com/WaJO6cY.gif)

# Editierte Nachrichten LOG
Diese RAW Data müsst ihr zu euren **Events** packen.

**Zu Beachten:**
- **ACTION #6** gebe dort deine **Channel ID** ein wo es geloggt werden soll

![github-large](https://i.imgur.com/k69F7ac.gif)

# Editierte Usernamen LOG
Diese RAW Data müsst ihr zu euren **Events** packen.

**Zu Beachten:**
- **ACTION #7** gebe dort deine **Channel ID** ein wo es geloggt werden soll

![github-large](https://i.imgur.com/LymT1xJ.gif)

# Das Mention LOG
Es stehen euch 2 Raw Datas zur Verfügung **mention-log** und **mention-log-on/off**
Beide Raw Datas werden als Command hinzugefügt.

**Befehle:**
- !mention-log | Einleitungsseite
- !mention-log #channel | Log Channel setzen wo es Protokolliert wird 
- !mention-log aus | Deaktivieren des Mention Logs

![github-large](https://i.imgur.com/MJL9En1.png)

# BOT ERROR LOG
Diese RAW Data müsst ihr zu euren **Events** packen.

**Zu Beachten:**
- **ACTION #4** gebe dort deine **Channel ID** ein wo es geloggt werden soll
- **ACTION #11** gebe hier die ID des Admins / Bot Owner ein der Erwähnt werden soll z.b. <@123456789123456789

![github-large](https://i.imgur.com/GWcUa37.png)

