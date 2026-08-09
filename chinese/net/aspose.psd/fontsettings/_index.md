---
title: "类 FontSettings"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FontSettings 类。通用 PSD 矢量格式渲染器的字体设置"
type: docs
weight: 4760
url: /zh/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

通用 PSD 矢量格式渲染器字体设置。

```csharp
public static class FontSettings
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | 获取或设置字体的默认名称。 |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | 获取或设置一个值，以指示是否 [get alternative font]。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | 清除所有字体替换 |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | 根据字体族名称获取 Adobe 字体名称。 |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | 获取默认的字体文件夹。 |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | 根据字体名称获取字体替换数组 |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | 获取包含 Aspose.Words 查找 TrueType 字体的文件夹列表的数组副本。 |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | 获取最合适的替代字体。如果所有替代字体均不被允许，则返回第一个允许且可用的字体。如果没有可用的字体，则返回参数中的字体。 |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | 确定是否 [is font allowed] [指定的字体名称]。 |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | 删除字体缓存文件。 |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | 将字体文件夹和默认字体名称重置为系统默认值。 |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | 通过字体列表限制字体使用。请在限制前检查真实的字体名称。将允许的字体列表设置为 Null 可移除限制。 |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | 设置字体替换列表。如果字体不被允许，则寻找替代字体。列表中的第一个字体将首先使用。如果它也被限制，则选择列表中的下一个字体。如果字体没有替代或所有替代均不被允许，则使用允许字体列表中的第一个允许的字体。如果没有允许且可用的字体，库将尝试使用系统默认字体，即使它不被允许。 |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | 这是一个指向 [`SetFontsFolders`](./setfontsfolders/) 的快捷方式，用于仅设置一个字体目录。不会对字体文件夹进行任何检查。 |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | 设置加载 TrueType 字体的文件夹并清除所有已加载的字体。不会对字体文件夹进行任何检查。 |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | 更新包含文本图层的 PSD 文件的字体缓存。此方法保证在处理 PSD 文件时，会考虑在使用 FontSettings.SetFontsFolder(fontsFolder) 方法指定的 fontsFolder 文件夹中的字体，或在使用 FontSettings.Reset() 重置字体后。请在每次为 PSD 图像调用 FontSettings.SetFontsFolder(fontsFolder) 或 FontSettings.Reset() 时使用此方法。如果不调用此方法，则无法保证字体会被更新。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


