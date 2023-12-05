# CZLibarclite-Files
解决Xcode升级14.3之后缺少libarclite_iphonesimulator.a文件的问题

 

由于XcodeDefaults工具链内容中没有“.a”文件，Xcode 14.3和14.3.1在某些Cocoa pod中存在构建问题。

以上是Xcode 14.3中丢失的所有文件。

您可以到以下路径：

>/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/


注意：如果lib文件夹不存在，请在该文件夹中创建一个名为“arc”的文件夹。
