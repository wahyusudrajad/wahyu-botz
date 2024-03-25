### wahyu-botz
> bot whtasapp multi device
> Script ini gratis, menggunakan 99% api dari [AlyaChan-APIs](https://api.alyachan.biz.id)

### Yang dibutuhkan
- [x] Server
- [x] WhatsApp
- [x] ffmpeg
- [x] imagemagick

### Settings di config.js
```Javascript
global.owner = [
    ['6283150866279'],
    ['6283150866279'],
    ['6283150866279', 'owner', true]
]

global.mods = ['0']
global.prems = ['6283150866279', '6283189910485']

global.APIs = {
  alya: 'https://api.alyachan.biz.id'
}

global.APIKeys = {
  'https://api.alychan.biz.id', 'YOURKEY'
}

global.set = {
  link: 'https://chat.whatsapp.com/EIe1hJspvpj3pzXYckeHkh',
  thumbnail: 'https://i.ibb.co/gtr5L2k/Supermoon-2012.jpg',
  wm: 'Wahyu-Botz',
  footer: 'Whatsapp Bot By Wahyu-Botz',
  packname: 'Sticker By',
  author: '@wahyusudrajad'
}

global.multiplier = 7
global.max_upload = 70
global.intervalmsg = 1800
```

### Plugins
```Javascript
let handler = async (m, {
  usedPrefix,
  command,
  args
}) => {
  try {

  } catch (e) {
    console.log(e)
  }
}
handler.help = ['command']
handler.tags = ['category']
handler.command = /^(command)$/i
module.exports = handler

```

### Instalasi & Run
```
$ npm install
$ npm start
```

menggunakan PM2

```
$ npm install pm2 -g
$ npm install
$ pm2 start index.js && pm2 save && pm2 logs
```

### Argumen `node . [--options]`

Contoh : node . --autread

### `--self`

Mengabaikan yang lain

### `--autoread`

autored chat

### `--db`

contoh : `node . --db 'mongodburi'`
Untuk menghubungkan ke database, pakai mongodb


----|----
[Nurutomo](https://github.com/wahyusudrajad) | [Wahyu-Botz](https://github.com/wahyusudrajad)
 Penulis / Pencipta | Penerjemah
