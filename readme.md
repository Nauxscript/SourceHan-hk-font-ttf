# 思源宋体繁体 `TTF` 版本
- 方便`Kodi`等只支持`ttf`字体的软件使用
- 使用`github action`进行自动转换

## 本转换字体包含
- 思源宋体繁体 TTF
- 思源宋体繁体港版 TTF

## 转换处理细节
- 仅转换 `TraditionalChinese` 和 `TraditionalChineseHK` 的版本
- 使用[otf2ttf](https://github.com/awesometoolbox/otf2ttf) 进行转换
- 因为`otf2ttf`转换缓慢, github actions 转换一个otf文件大概需要3-5分钟, 所以仅转换官方 release 的 `-Bold` 文件，如有需要可以 folk 项目后，根据压缩文件地址下载的文件的解压后的目录结构进行调整

## 压缩地址参考

详见 [github_action.yaml](./.github/workflows/sourcehan_font_ttf.yml)

- TraditionalChinese: https://github.com/adobe-fonts/source-han-serif/releases/download/2.001R/10_SourceHanSerifTC.zip
- TraditionalChineseHK: https://github.com/adobe-fonts/source-han-serif/releases/download/2.001R/11_SourceHanSerifHC.zip

## 开源协议
- 本项目采用[MIT协议](https://github.com/gek64/SourceHan-font-ttf/raw/main/LICENSE)

## ✨感谢

感谢 [@gek64](https://github.com/gek64)!
