# iOS Images Extractor

### 本项目 fork 自 https://github.com/devcxm/iOS-Images-Extractor 下载下来直接就可以运行。主要改动是修复解压出来的文件命名的问题，基本是用来解压 Assets.car 文件。

### 目前都解压不出 @3x 图片，可以试试我提供的脚本，适合自己的项目https://gist.github.com/crespoxiao/82c2fcc0fd08132e8b49e5116b282ab8



* cartool 和 AssetCatalogTinkerer 都不能把 Assets.car 里面的 3X 图片解压出来。
* https://github.com/steventroughtonsmith/cartool
* https://github.com/insidegui/AssetCatalogTinkerer
* http://stackoverflow.com/questions/22630418/analysing-assets-car-file-in-ios 
* http://stackoverflow.com/questions/21857986/how-can-i-load-an-image-from-assets-car-compiled-version-of-xcassets-within-an 
* http://blog.startry.com/2016/03/17/the-trap-of-image-resource/




iOS Images Extractor is a Mac app to normalize , decode and extract images from iOS apps.You can download binary release from the [latest releases](https://github.com/devcxm/iOS-Images-Extractor/releases/latest). (Sorry for my bad English)

![logo](https://raw.githubusercontent.com/devcxm/iOS-Images-Extractor/master/iOSImagesExtractor/iOSImagesExtractor/Images.xcassets/AppIcon.appiconset/AppIcon-256.png)

## Support Files
- `png、jpg`
- `ipa`
- `car(Assets.car)`

## Build
```
git clone git@github.com:crespoxiao/iOSImagesExtractor.git
open iOSImagesExtractor.xcworkspace
```
### [中文使用方法看这里](/README_zh-Hans.md)

## Screenshot
![(Screenshot)](https://cloud.githubusercontent.com/assets/8568955/7927878/874f0594-0918-11e5-9fe3-452372f5affd.gif)

## Requirements
_**OS X 10.8 or later.**_

## License

iOS Images Extractor is released under the MIT license. See [LICENSE](/LICENSE) for details.
