# NocodeObjC

NocodeObjC是一个ObjC低代码平台，包含了ObjC开发中常用的开源库。

## 目录

* [包管理工具](#packagemanager)
  * [cocoapods](#cocoapods)
  * [carthage](#carthage)

* [网络](#networking)
  * [HTTP——AFNetworking](#AFNetworking)
  * [Socket——CocoaAsyncSocket](#CocoaAsyncSocket)
  * [WebSocket——SocketRocket](#SocketRocket)

* [日志](#logging)
  * [CocoaLumberjack](#CocoaLumberjack)

* [UI](#UI)
  * [Autolayout——Masonry](#Masonry)
  * [菊花——MBProgressHUD](#MBProgressHUD)
  * [菊花——SVProgressHUD](#SVProgressHUD)
  * [键盘——IQKeyboardManager](#IQKeyboardManager)
  * [YYKit](#YYKit)
  * [WebViewJavascriptBridge](#WebViewJavascriptBridge)
  * [图表——PNChart](#PNChart)
  * [炫酷UI——FlatUIKit](#FlatUIKit)

* [Image](#Image)
  * [GIF——FLAnimatedImage](#FLAnimatedImage)
  * [缓存——SDWebImage](#SDWebImage)
  * [TZImagePickerController](#TZImagePickerController)

* [UITableView/UICollectionView](#tablecollection)
  * [空列表——DZNEmptyDataSet](#DZNEmptyDataSet)
  * [IGListKit](#IGListKit)
  * [FDTemplateLayoutCell](#FDTemplateLayoutCell)

* [加解密](#crypto)

* [Model层](#modeling)
  * [Mantle](#Mantle)
  * [MJExtension](#MJExtension)
  * [RestKit](#RestKit)

* [数据存储](#localstorage)
  * [SQLite——FMDB](#FMDB)
  * [realm](#realm)
  * [MagicalRecord](#MagicalRecord)

* [社交分享](#socialmedia)
  * [facebook](#facebook)
  * [微信](#wechat)
  * [QQ](#QQ)
  * [腾讯开放平台](#tencent)
  * [微博](#weibo)

* [响应式编程](#Reactive)
  * [ReactiveCocoa](#ReactiveCocoa)

* [App内调试](#debug)
  * [FLEX](#FLEX)

* [跨平台开发](#multiplatorm)

## <span id="packagemanager">包管理工具</span>

### <span id="cocoapods">cocoapods</span>
 
首页：https://cocoapods.org/
 
### <span id="carthage">carthage</span>

首页：https://github.com/Carthage/Carthage

## <span id="networking">网络</span>

### <span id="AFNetworking">AFNetworking</span>

HTTP网络库，基于原生提供NSURLSession实现。请参考：

https://github.com/AFNetworking/AFNetworking

### <span id="CocoaAsyncSocket">CocoaAsyncSocket</span>

第三方封装的Socket实现。请参考：

https://github.com/robbiehanson/CocoaAsyncSocket

### <span id="SocketRocket">SocketRocket</span>

使用ObjC实现的WebSocket。请参考：

https://github.com/facebookincubator/SocketRocket

## <span id="logging">日志</span>

### <span id="CocoaLumberjack">CocoaLumberjack</span>

苹果平台上简易快速的日志库。请参考：

https://github.com/CocoaLumberjack/CocoaLumberjack

## <span id="UI">UI</span>

### <span id="Masonry">Masonry</span>

Autolayout的简化易用库。请参考：

https://github.com/SnapKit/Masonry

### <span id="MBProgressHUD">MBProgressHUD</span>

菊花神器。请参考：

https://github.com/jdg/MBProgressHUD

### <span id="SVProgressHUD">SVProgressHUD</span>

有一个菊花。请参考：

https://github.com/SVProgressHUD/SVProgressHUD

### <span id="IQKeyboardManager">IQKeyboardManager</span>

键盘管理。请参考：

https://github.com/hackiftekhar/IQKeyboardManager

### <span id="YYKit">YYKit</span>

YYKit提供多种UI工具，设计图片、键盘、model层等等。
 
https://github.com/ibireme/YYKit

### <span id="WebViewJavascriptBridge">WebViewJavascriptBridge</span>

WebView的js桥。请参考：

https://github.com/marcuswestin/WebViewJavascriptBridge

### <span id="PNChart">PNChart</span>

图表库。请参考：

https://github.com/kevinzhow/PNChart

### <span id="FlatUIKit">FlatUIKit</span>

实现各种UI效果库、各种UI工具，如背景色、阴影等。请参考：

https://github.com/Grouper/FlatUIKit

## <span id="Image">Image</span>

### <span id="FLAnimatedImage">FLAnimatedImage</span>

处理GIF的图片库。请参考：
 
https://github.com/Flipboard/FLAnimatedImage

### <span id="SDWebImage">SDWebImage</span>

图片缓存框架。请参考：

https://github.com/SDWebImage/SDWebImage

### <span id="TZImagePickerController">TZImagePickerController</span>

自定义ImagePicker。请参考：

https://github.com/banchichen/TZImagePickerController

## <span id="tablecollection">UITableView/UICollectionView</span>

### <span id="DZNEmptyDataSet">DZNEmptyDataSet</span>

列表为空时，显示不同提示给用户。请参考：

https://github.com/dzenbot/DZNEmptyDataSet

### <span id="IGListKit">IGListKit</span>

数据驱动的CollectionView。请参考：

https://github.com/Instagram/IGListKit

### <span id="FDTemplateLayoutCell">FDTemplateLayoutCell</span>

自动布局TableViewCell，动态计算高度。请参考：

https://github.com/forkingdog/UITableView-FDTemplateLayoutCell

## <span id="crypto">加解密</span>

## <span id="modeling">Model层</span>

### <span id="Mantle">Mantle</span>

Mantle是处理Model简单易用工具。请参考：

https://github.com/Mantle/Mantle

### <span id="MJExtension">MJExtension</span>

字典、字典数组、json、对象相互转化的工具。请参考：

https://github.com/CoderMJLee/MJExtension

### <span id="RestKit">RestKit</span>

RESTful Web service终端，提供多种功能，如Model映射等。请参考：

https://github.com/RestKit/RestKit

## <span id="localstorage">数据存储</span>

### <span id="FMDB">FMDB</span>

FMDB是一个SQLite封装库。请参考：

https://github.com/ccgus/fmdb

### <span id="realm">realm</span>

realm是一个替代CoreData、SQLite的数据库。请参考：

https://github.com/realm/realm-cocoa

### <span id="MagicalRecord">MagicalRecord</span>

CoreData简化库。请参考：

https://github.com/magicalpanda/MagicalRecord

## <span id="socialmedia">社交分享</span>

### <span id="facebook">facebook</span>

facebook ios SDK。请参考：

https://github.com/facebook/facebook-ios-sdk

### <span id="wechat">微信</span>

微信登录、分享、支付等等，微信开放平台。请参考：

https://open.weixin.qq.com/

### <span id="QQ">QQ</span>

qq登录、分享等等，qq互联平台。请参考：

https://connect.qq.com/

### <span id="tencent">腾讯开放平台</span>

腾讯系所有应用开放平台，包括微信、qq、qq空间、应用宝、AI等。请参考：

https://open.tencent.com/

### <span id="weibo">微博</span>

微博登录、分享等等，微博开放平台。请参考：

https://open.weibo.com/

## <span id="Reactive">响应式编程</span>

### <span id="ReactiveCocoa">ReactiveCocoa</span>

ObjC响应式编程。请参考：

https://github.com/ReactiveCocoa/ReactiveCocoa

## <span id="debug">App内调试</span>

### <span id="FLEX">FLEX</span>

App内调试工具。请参考：

https://github.com/FLEXTool/FLEX

## <span id="multiplatorm">跨平台开发</span>


