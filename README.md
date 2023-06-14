# 解决Xcode 14.3跑工程报错
> File not found: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a


将仓库clone之后,把目录下的文件挪到
`/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/`下.如果没有`arc`目录,自行创建