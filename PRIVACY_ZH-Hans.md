# sCollectPlay 和 sCollectPlay Lite 隐私政策

更新日期：2026-10-23

## 摘要

sCollectPlay 和 sCollectPlay Lite **不会**收集、存储或传输任何个人数据。这两个 App 只在你的 Mac 或 Windows 电脑上工作。没有账户，没有云端连接，没有分析服务，也没有广告。

## App 处理哪些数据

App 只读取你明确交给它的那些文件夹里的媒体文件 —— 通过在打开对话框中选择：一个要扫描的文件夹、
一个 iTunes 或 Apple Music XML，或者一个 sCollect 媒体库。读取的是文件名、文件大小、日期和文件的
元数据，对于 XML 或媒体库，还包括其中的目录信息。

没有你的选择，App 不会访问任何文件。macOS 通过 App 沙盒来保证这一点。

## App 在你的 Mac 上存放什么

- **设置和窗口位置**，位于 App 受保护的专属文件夹中。
- **macOS 的许可，让 App 下次启动时能重新打开你的文件夹。** 保存的是文件夹路径，不是文件内容。
  只有这样，App 才不必每次启动都重新询问。
- **sCollectPlay 另外还会保存：** 最近使用的文件夹、XML 文件和媒体库的列表，你自建的播放列表，
  排序方式以及列浏览器的状态 —— 同样位于 App 受保护的专属文件夹中。

只要你删除 App，这些内容也就一并消失。

## 两项可能引起疑问的权限

**网络访问权限。** App 之所以申请它，是因为没有这项权限时 macOS 会把内置的帮助窗口显示为空白
—— 帮助是由一个需要该权限的系统组件呈现的，即使它只加载程序自身的文件。App 自己**不会访问
互联网上的任何地址**，不下载任何东西，也不上报任何东西。

位于网络驱动器（SMB、NFS）上的文件夹，App 是通过你 Mac 的文件系统访问的，而不是通过自己的
连接。

**控制 Apple Music。** 当你把一个选择作为播放列表发送到 Apple Music 时，App 会用生成的播放列表
打开 Apple Music，并可按你的意愿替换那里已有的同名播放列表。为此 macOS 需要你的同意，并会在
第一次时询问。除此之外，App 不会控制任何其他程序。

## 你的文件

App 不写入标签，也不更改你文件的元数据。

当你打开一个 sCollect 媒体库时，App 会把你的评分和播放次数（含日期和时间）保存到该媒体库文件夹中的 `rueckmeldungen.json` 文件里，以便 sCollect 接收这些信息。App 不会更改媒体库本身和媒体文件，这些信息也不会离开你的电脑。

只有当你明确删除某个文件时，App 才会把它移到 macOS 的废纸篓，并将其从列表中移除；如果它来自
某个 sCollect 媒体库，该媒体库的目录也会相应更新。在没有废纸篓的驱动器上，App 会先询问是否
要永久删除该文件。

## 在 Windows 上

以上内容描述的是 Mac。在 Windows 上，sCollectPlay 和 sCollectPlay Lite 只把以下内容保存在本地、App 自己的数据
文件夹中（`%LOCALAPPDATA%\Packages\<程序包>\LocalState` 和 `Settings`）：

- **设置和窗口位置。**
- **最近一次选择的来源** —— 扫描过的文件夹、一个 iTunes XML 文件或一个 sCollect 媒体库 —— 以及上一次扫描的结果。
- **媒体库在 Mac 上的文件夹与你电脑上文件夹的对应关系**（仅文件夹路径）。
- **sCollectPlay 另外还会保存：** 你自建的播放列表、最近使用的文件夹、XML 文件和媒体库的列表、排序方式以及
  分栏浏览器的状态。
- **错误日志**（`fehler.log`），它只留在你的电脑上。

卸载 App 时，这些内容会全部删除。

App 只在你选择的位置读取媒体文件和 XML 文件；sCollect 媒体库只会被读取（“你的文件”中所述的 `rueckmeldungen.json` 文件除外）。App 不会自行建立网络连接，不使用分析服务，
也没有广告。Windows 自身无法播放的文件，会交给该文件类型的默认程序，默认程序由你在 Windows 中选择。

在 sCollectPlay 中为 VLC 或设备导出播放列表时，App 会把其中的文件复制到你选择的文件夹。

只有当你明确删除来自扫描过的文件夹或 iTunes XML 的某个媒体文件时，App 才会把它移到 Windows 的回收站；在没有
回收站的驱动器上（例如网络上），App 会先询问，然后永久删除该文件。sCollect 媒体库不会因此改变。

## Microsoft Store

在 Windows 上，购买（sCollectPlay）、下载和更新都通过 Microsoft Store 进行，适用 Microsoft 的隐私声明。
sCollectPlay Lite 是免费的，并会提及完整版。

## 不转交，不分析

没有广告，没有分析服务，没有发给第三方的崩溃报告，也没有账户。

## 联系方式

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
