
<h1 align="center">
  <img src="src-tauri/icons/128x128.png" width="128" />
  <br>
  Video Downloader
  <br>
</h1>

<h3 align="center">
 Cross-platform video(Douyin/Bilibili) download tool built with <a href="https://github.com/tauri-apps/tauri">tauri</a>.
</h3>
<div align="center">

[![Windows Support](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)](https://github.com/ClassmateLin/douyin-downloader/releases)
[![MacOS Support](https://img.shields.io/badge/MACOS-adb8c5?style=flat&logo=macos&logoColor=white)](https://github.com/ClassmateLin/douyin-downloader/releases)
[![Linux Support](https://img.shields.io/badge/linux-1793D1?style=flat&logo=linux&logoColor=white)](https://github.com/ClassmateLin/douyin-downloader/releases)

</div>

[ä¸­æææ¡£](./README_cn.md)

## Install


Download from [release](https://github.com/ClassmateLin/douyin-downloader/releases). Supports Windows x64, Linux x86_64 and macOS 11+

Or you can build it yourself. Supports Windows, Linux and macOS 10.15+

Notes: If you could not start the app on Windows, please check that you have Webview2 installed.


## Development

**You should install Rust and Nodejs.**

- Pull code and install dependencies:

```
$ git clone https://github.com/ClassmateLin/douyin-downloader.git && cd douyin-downloader
$ npm install
```

- Starting the development server can be done with: `npm run tauri dev`


- Creating a build can simply be done with: `npm run tauri build`


## ð Features / Todos

### Douyin

#### Single video download

- [x] Search video by sharing link. eg: `https://v.douyin.com/jpL1UwY/` or `5.30 WZZ:/ å¤å¶æå¼æé³ï¼ççãéä¹¦äººçä½åã# äººçææ # å²çäººç # ä¹¦å # æºæ§äººç @æé³... https://v.douyin.com/643hUux/`
- [x] Preview the searched video.
- [x] Download the searched video.

#### Multiple video download

- [x] Search all videos by user homepage url. eg: `https://v.douyin.com/j3XPKMg/` or `8- é¿æå¤å¶æ­¤æ¡æ¶æ¯ï¼æå¼æé³æç´¢ï¼æ¥çTAçæ´å¤ä½åã https://v.douyin.com/64w7StG/`
- [x] Download all videos in batch.
- [x] Batch download selected videos.
- [x] Download/preview a single video in a table.


## Screenshot

![index](./docs/imgs/index.png)

![douyin_single_search](./docs/imgs/douyin_single_search.png)

![douyin_single_download](./docs/imgs/douyin_single_download.png)

![douyin_multi_search](./docs/imgs/douyin_muplit_search.png)

![douyin_single_download](./docs/imgs/douyin_muplit_download.png)