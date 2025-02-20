# @ytdl/han they have done it with nodejs 

```bash
npm install github:HanSamu-27/@ytdl/han
```

## Uso

```nodejs
//塞缪尔和吉娜
const ytdl_han = require("@ytdl/han")

(async () => {
var gi = await ytdl_han("https://youtu.be/cCmfIDhGokM?si=NSZesdBc2jaPOWxP", "128kbps") //quality options - 1080p, 360p, 720p || 128kbps(audios)
console.log(`-─     ☁️     ネ   Title: ${gi.data.title}`)
console.log(`-─     ☁️     ネ   Size: ${gi.data.size}`)
console.log(`-─     ☁️     ネ   thumbnail: ${gi.data.size}`)
console.log(`-─     ☁️     ネ   Id: ${gi.data.id}`)
console.log(`-─     ☁️     ネ   audio/video: ${gi.data.format}`) //If it is video, just use fs and convert it to Mp4 format and if it is audio, 128kbps to Mp3
})()
```

# Creator

[![Owner](![Youtube](https://telegra.ph/file/d374b0dfd9d9d159c0f56.jpg))](https://wa.me/+5219983369376?text=Hola+Han+:3)
