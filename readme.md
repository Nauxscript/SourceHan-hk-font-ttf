# 思源宋体香港繁体 `TTF` 版本
- 方便`Kodi`等只支持`ttf`字体的软件使用
- 使用`github action`进行自动转换

## 思源字体包含
- [思源黑体](https://github.com/adobe-fonts/source-han-sans) SC
- [思源宋体](https://github.com/adobe-fonts/source-han-serif) SC
- 思源黑体 SC TTF
- 思源宋体 SC TTF

## 转换处理细节
- ~~仅转换SC版本 `SourceHanSansSC` `SourceHanSerifSC`, `SC`版本指的是简体中文版~~ 
- 仅转换 `TraditionalChineseHK` 的版本
- 使用[otf2ttf](https://github.com/awesometoolbox/otf2ttf) 进行转换
- 因为`otf2ttf`转换缓慢, github actions 转换一个otf文件大概需要3-5分钟, 所以仅转换官方 release 的 `OTF/TraditionalChineseHK/SourceHanSerifHC-Bold.otf` 文件，如有需要可以 folk 项目后，根据 `https://github.com/adobe-fonts/source-han-serif/releases/download/2.001R/11_SourceHanSerifHC.zip` 地址下载的文件的解压后的目录结构进行调整

## 开源协议
- 本项目采用[MIT协议](https://github.com/gek64/SourceHan-font-ttf/raw/main/LICENSE)

## ✨感谢

感谢 [@gek64](https://github.com/gek64)!
