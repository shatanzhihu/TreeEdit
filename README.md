# TreeEdit

纯Qml实现的树结构编辑器。

使用Controls2 中的 ListView 和 ListModel模拟实现。

|功能|进度|
|--|--|
|树结构的缩进|完成|
|展开、折叠|完成|
|添加|完成|
|删除|完成|
|重命名|完成|
|搜索|完成|
|导入|计划中|
|导出|计划中|
|节点属性编辑|计划中|

## 更新(2019/12/13)

ListModel嵌套的情况下，内部js object被转换成了ListModel，导入/导出有问题，不能正确拿到数据。

Qt5.14说修复了这个bug，但是运行的时候程序直接崩溃了。

后续会把model改成C++的model，顺便支持一下大数据。

## 效果预览

![](preview.png)
## Qt版本

5.12.x

## status

| [Windows][win-link]| [Ubuntu][ubuntu-link]|[MacOS][macos-link]|[Android][android-link]|[IOS][ios-link]|
|---------------|---------------|-----------------|-----------------|----------------|
| ![win-badge]  | ![ubuntu-badge]      | ![macos-badge] |![android-badge]   |![ios-badge]   |


[win-link]: https://github.com/JaredTao/TreeEdit/actions?query=workflow%3AWindows "WindowsAction"
[win-badge]: https://github.com/JaredTao/TreeEdit/workflows/Windows/badge.svg  "Windows"

[ubuntu-link]: https://github.com/JaredTao/TreeEdit/actions?query=workflow%3AUbuntu "UbuntuAction"
[ubuntu-badge]: https://github.com/JaredTao/TreeEdit/workflows/Ubuntu/badge.svg "Ubuntu"

[macos-link]: https://github.com/JaredTao/TreeEdit/actions?query=workflow%3AMacOS "MacOSAction"
[macos-badge]: https://github.com/JaredTao/TreeEdit/workflows/MacOS/badge.svg "MacOS"

[android-link]: https://github.com/JaredTao/TreeEdit/actions?query=workflow%3AAndroid "AndroidAction"
[android-badge]: https://github.com/JaredTao/TreeEdit/workflows/Android/badge.svg "Android"

[ios-link]: https://github.com/JaredTao/TreeEdit/actions?query=workflow%3AIOS "IOSAction"
[ios-badge]: https://github.com/JaredTao/TreeEdit/workflows/IOS/badge.svg "IOS"
