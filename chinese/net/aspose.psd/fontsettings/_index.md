---
title: FontSettings
second_title: Aspose.PSD for .NET API 参考
description: 通用 PSD 矢量格式渲染器字体设置
type: docs
weight: 4170
url: /zh/net/aspose.psd/fontsettings/
---
## FontSettings class

通用 PSD 矢量格式渲染器字体设置。

```csharp
public static class FontSettings
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname) { get; set; } | 获取或设置字体的默认名称。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements)() | 清除所有字体替换 |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname)(string) | 按字体系列名称获取 adobe 字体名称。 |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders)() | 获取默认字体文件夹。 |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements)(string) | 通过字体名称获取字体替换数组 |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders)() | 获取数组的副本，其中包含 Aspose.Words 查找 TrueType 字体的文件夹列表。 |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont)(string) | 获取最合适的替换字体。 如果不允许所有替换，则将返回第一个允许且可用的字体。 如果没有可用的字体，那么将从参数 |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed)(string) | 确定[是否允许使用字体][指定的字体名称]。 |
| static [Reset](../../aspose.psd/fontsettings/reset)() | 将字体文件夹和默认字体名称重置为系统默认值。 |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts)(string[]) | 按字体列表限制字体使用。请在限制前检查真实字体名称 将允许的字体列表设置为 Null 以删除限制 |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements)(string, string[]) | 设置字体替换列表。如果字体不允许，则将查找替换。 列表中的第一个字体将首先使用。如果它也被限制，那么将从列表中选择下一个字体。 如果字体没有替换或不允许所有替换，则将使用允许字体列表中的第一个允许字体。 如果没有允许和可用的字体，那么即使不允许，库也会尝试使用系统默认字体。 |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder)(string) | 这是[`SetFontsFolders`](./setfontsfolders)的快捷方式，用于仅设置一个字体目录。 没有对字体文件夹进行检查。 |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders)(string[], bool) | 设置加载 TrueType 字体的文件夹并清除所有加载的字体。 没有对字体文件夹进行检查。 |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts)() | 更新包含文本层的 PSD 文件的字体缓存。此方法保证在处理 PSD 文件时，将考虑使用 方法 FontSettings.SetFontsFolder(fontsFolder) 或使用 FontSettings.Reset() 重置字体后来自文件夹 fontsFolder 的字体。每次 FontSettings.SetFontsFolder(fontsFolder) 或 FontSettings.Reset() 调用 PSD 图像时，请使用此方法。如果不调用此方法，则无法保证字体会被更新。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
