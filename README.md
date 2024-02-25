# tiktokdownloader
Download video Tiktok
# TikTok Downloader

Modul ini memungkinkan Anda mengunduh video TikTok.

## Instalasi

Anda dapat menginstal modul ini menggunakan npm:

```bash
npm install tiktokdownloader
```

### USO
```bash
const tk = require('tiktokdownloader');

const url = 'https://www.tiktok.com/@andx.vx/video/7324208424709836038';

async function main() {
  try {
    const result = await tk.tiktokdownload(url);
    console.log(result);
  } catch (error) {
    console.error('Error:', error.message);
  }
}

main();

```
