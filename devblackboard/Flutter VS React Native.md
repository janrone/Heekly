Flutter VS React Native 

目前移动端跨端方案，无外乎这两种。作者比较了两个方案的各方面特点，下面我当课代表总结一下丷 

Flutter is better than React Native*
https://shift.infinite.red/flutter-is-better-than-react-native-fed10c92a768


![](https://files.mdnice.com/user/8292/5d018d63-451e-4999-a441-c3b6933d1411.png)

首先，在讨论 Flutter 和 React Native 那一个更好时，最重要的问题是什么？  
答案是 人才！人才还是人才！  

1. RN 依托 JavaScript 生态有大量的人才可以寻找， Dart 却不是。  
所以即便在很多地方 RN 做的不够出色，但也阻止不了他的流行。

2. 开发体验：Flutter 开发体验比 React Native 出色很多。即便 React Native正在迎头赶上，但依然还有一段路要走（但Expo给了它一个强大的助力）。  
Flutter 胜出

3. 性能： 比较性能是一件困难的事情。多数情况下 Flutter和React Native 都是 "足够快 "的，**特别是当有能力的开发者对它们进行了性能优化之后。**  

- 不过 Flutter 的性能包袱更小，out-of-the-box 性能更优。  
- 所以 Flutter 略微胜出（目前是这样的，等待RN的新框架）。

4. UI一致性（1）：
Flutter 使用 Skia 绘制 UI，所以跨端 UI 非常一致。React Native在iOS上使用UIKit，在Android上使用Android的布局系统，在Web上使用DOM。虽然可以建立非常相似的应用程序，但它们将被每个平台的解释所影响。 

5. UI一致性（2）：
需要指出的是 It’s worth noting that Google developers have said that a unified experience is no longer a core goal. 
作者认为「在匹配用户期望」也就是 Android 要有 Android 的样子，iOS 要有 iOS 的样子 这件事情上， RN 的方式更好。  （在国内可能比不是）

6. 整合原生的能力：
Flutter 非好的工具链，你可以直接写 Swift 和 Kotlin，官方的文档都有很详细的说明。而 RN 在这件事情上，需要和 React Native bridge 打交道，不仅受限于此，在文档上也和 Flutter 有差距。（不过新版框架将替换掉 bridge）  
所以 Flutter 更胜一筹。  

7. 国际化：
Flutter 内置出色方案，RN 第三方方案同样优秀。  / 打平手  
8. 导航/路由 等：
Flutter 提供内置导航，RN 第三方同样出色  /难分伯仲  
对网页的支持：
React Native可以直接在项目内共享跨端代码，Flutter 不太行。即便提供了 HTML/CSS/DOM 的操作能力，依然很难和一等公民抗争。  RN胜

9. 第三方生态：
Flutter 有一些优秀的第三方扩展，但是和庞大的 JS 生态相比，还是稍显单薄。  总结，Flutter 基本够用， RN 五彩缤纷。 RN 胜出。
大公司使用与支持：
RN：微软和 Meta 是主要的支持者。
Flutter： Google 力推。

10. 动态（热）更新：
一些大公司以后规避上架更新的需求，RN 更容易实现这个目标。Flutter 这边则没有相关的计划。  
RN 胜  
---
完！
大家来说说你的看法吧！