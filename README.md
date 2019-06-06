# tongzhong-music
<a href="./README_en.md">English</a>
<p>呃，现在好像不能“在一处聆听所有音乐”了。因为QQ音乐为了推广它的客户端，已经不再支持在 Web 上播放周杰伦的歌了。</p>
<p>注意：该网站是 <a href="http://tongzhong.xyz">tongzhong.xyz</a> 的阉割版。</p>

## 功能
### 桌面版
- 搜索
 (支持使用查询字符串搜索，如: <a href="http://tongzhong.xyz/search?keyword=Iron%20Man&type=song" >http://tongzhong.xyz/search?keyword=Iron%20Man&type=song</a>.)
- 播放
- 热歌榜（包括QQ音乐和网易云音乐）
- 记录搜索历史

<img src="./screenshots/desktop.png" alt="desktop">

### 移动版
- 搜索
- 播放

<img src="./screenshots/m.png" alt="mobile">

## 使用
    # Install dependencies
    npm install
    # Build client-side bundle
    npm run build
    # Start the server
    npm run server
打开 `http://localhost:8081` 即可。

## 开发
### 后端
    # Start nodemon dev server (需要全局安装 nodemon)
    npm run dev-server

### 前端
    # Start webpack dev server
    npm start
<p>桌面版打开 `http://localhost:3000`，移动版打开`http://localhost:3000/m`。</p>

## 致谢
- <a href="https://github.com/Binaryify/NeteaseCloudMusicApi">Binaryify/NeteaseCloudMusicApi</a>
- <a href="https://github.com/LIU9293/musicAPI">LIU9293/musicAPI</a>
<p>如果 GitHub 有“感谢”按钮的话，我一定再给你们点个感谢！</p>

## License
MIT
