---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD for .NET API 参考"
description: "FontSettings 方法。删除字体缓存文件。"
type: docs
weight: 100
url: /zh/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

删除字体缓存文件。

```csharp
public static void RemoveFontCacheFile()
```

## 示例

以下代码演示了删除已加载字体缓存文件的方法。

```csharp
[C#]

string src = "SimpleText.psd";

FontSettings.RemoveFontCacheFile();

using (var psdImage = (PsdImage)Image.Load(src))
{
    foreach (var layer in psdImage.Layers)
    {
        if (layer is TextLayer textLayer)
        {
            textLayer.GetFonts();
        }
    }
}
```

### 另请参阅

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


