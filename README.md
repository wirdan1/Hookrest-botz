![Logo](https://i.supa.codes/y7Jm2W)

**😼 NekoBot | 1.0.0** | ***create by Hookrest Team***


```> Simple WhatsApp bot Using Library Baileys```

```javascript
{
  message: Message { conversation: '>_ Welcome to Hookrest Botz' },
  type: 'conversation',
  msg: '>_ Welcome to Hookrest Botz',
  isMedia: false,
  key: {
    remoteJid: '6285165556936@s.whatsapp.net',
    participant: '6285165556936@s.whatsapp.net',
    fromMe: false,
    id: '5780C33F89C0BE600B6D71DF79C4FC02'
  },
  cht: '6285165556936@s.whatsapp.net',
  fromMe: false,
  id: '5780C33F89C0BE600B6D71DF79C4FC02',
  device: 'android',
  isBot: false,
  isGroup: false,
  participant: '6285165556936@s.whatsapp.net',
  sender: '6285165556936@s.whatsapp.net',
  mentions: [],
  body: '>_ Welcome to Hookrest Botz',
  prefix: '',
  command: '>_',
  args: [ 'Welcome', 'to', 'Hookrest Botz' ],
  text: 'Welcome to Hookrest Botz',
  isOwner: true,
  download: [AsyncFunction (anonymous)]
}
```
## ⚙️ Settings Bot ***( settings.js )***

```javascript
const fs = require('node:fs');

const config = {
    owner: ["6285215909004"],
    name: "- Hookrest Botz - Simple WhatsApp bot",
    sessions: "sessions",
    sticker: {
      packname: "Made by ",
      author: "Hookrest Botz"
    },
   messages: {
      wait: "*( Loading )* Tunggu Sebentar...",
      owner: "*( Denied )* Kamu bukan owner ku !",
      premium: "*( Denied )* Fitur ini khusus user premium",
      group: "*( Denied )* Fitur ini khusus group",
   },
   database: "neko-db",
   tz: "Asia/Jakarta"
}

module.exports = config
```


## 👨‍💻 How to install/run


```bash
$ git clone https://github.com/wirdan1/Hookrest-bot
$ cd name file
$ npm install
$ npm start
```

## ☘️ Example Features
Berikut cara menambahkan fitur pada bot ini

## 1. Plugins

```javascript

module.exports = {
    command: "tes",
    alias: ["tesbot", "testing"],
    category: ["main"],
    settings: {
        owner: false,
        group: false,
     },
    description: "Tes bot saja",
    loading: true,
 async run(m, { sock, Func, Scraper, text, config }) {
    m.reply("> Bot Online ✓")
  }
}
```
## 2. Case

```javascript
case "tes" : {
     m.reply("> Bot Online ✓")
   }
break
```
## 📢 Promotin 
Thanks for
Neko team
Danz-dev
Hookrest Team
