# LRCsToWord-

将多个 LRC 文件里的歌词整合到一个 WORD 文件里方便打印，搭配 163MusicLyrics 使用

> 163MusicLyrics 这个项目可以下载网易云歌单的歌词
> 但是我想打印的话却有些麻烦，所以做了这个脚本可以整合 LRC 文件到一个 WORD 文件里进行打印

## 使用方法

1. 下载仓库把 LRC 歌词文件全放到 **歌词** 文件夹里
2. 在此文件夹右键打开 PowerShell，输入 `python LRCsToWord.py` 即可
3. 完成后会在此文件夹输入一个 word 文件

#### 注：需要安装 python 和 python-docx 库

- python-docx 库 安装办法：
  `pip install python-docx`
