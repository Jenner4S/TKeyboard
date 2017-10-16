### What is it?

TKeyboard enables you to use Mac keyboard to do typing on your iOS devices, it's based on bluetooth communication, super easy to set up.

### How to use?

Install both TKeyboard for iOS and TKeyboard for Mac, enable TKeyboard as keyboard extension on your iOS device, switch keyboard, you shall be able to establish a bluetooth connection between iOS and Mac, you are ready to go.

#### Download from App Store

you can also download TKeyboard from App Store, the iOS version costs 1.99$, buy me a cup of coffee if you don't mind ;)

TKeyboard for iOS App Store：[https://itunes.apple.com/cn/app/tkeyboard/id1168383839?l=zh&ls=1&mt=8](https://itunes.apple.com/cn/app/tkeyboard/id1168383839?l=zh&ls=1&mt=8)

TKeyboard for Mac App Store：[https://itunes.apple.com/cn/app/tkeyboard/id1168383849?l=zh&ls=1&mt=12](https://itunes.apple.com/cn/app/tkeyboard/id1168383849?l=zh&ls=1&mt=12)

#### Licence
GPL-3.0
应用场景
这款应用名为：TKeyboard。有一个 Mac 端和一个 iOS 端 App。简单来说，可以通过蓝牙，使用 Mac 的键盘输入内容到 iPhone 设备中。
主要是为了解决 iPhone 设备输入不方便的问题，有 Mac 在身边的时候会比较方便，一时脑洞的小应用。
 
涉及知识点
这两个 App 解决的用户场景比较完整，代码方面涉及到一些较为实用的技术点：
Mac 端开发，从 iOS 端切入 Mac 端开发其实难度比大部分人预想的都要小，主要是 UI Framework 需要做些学习，用 xib 配合 autolayout 其实很方便，就是做动画会稍微麻烦一些。
iOS 端的话，主要是各种 Extension 的开发学习，现阶段实现的是 Keyboard Extension，后期这个项目计划实现更多的 Extension 功能，最终的目标是成为一个 Mac 端和 iOS 端的多功能同步应用。Extension 开发的重要性，我曾经专门写文介绍过，不再赘述。
另外是蓝牙通讯这一块，iOS 端和 Mac 端共享一套代码。蓝牙这块网络上技术文章比较少，完整的开源项目几乎找不到。我在结合官方 demo 和自己踩坑的基础之上，基本实现了一套完整的蓝牙通讯功能。
最后还有一个简单的网络协议设计，用于 iOS 和 Mac 端做通讯之用，理论上使用 protobuf 更合理，但这是个人项目，处于写代码的乐趣，就自己动手 DIY 了一个，感兴趣的同学也可以自己设计
