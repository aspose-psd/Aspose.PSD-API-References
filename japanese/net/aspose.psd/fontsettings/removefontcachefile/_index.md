---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD for .NET API Reference"
description: "FontSettings メソッド。フォントキャッシュファイルを削除します。"
type: docs
weight: 100
url: /ja/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

フォントキャッシュファイルを削除します。

```csharp
public static void RemoveFontCacheFile()
```

## 例

以下のコードは、読み込まれたフォントのキャッシュファイルを削除するメソッドを示しています。

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

### 関連項目

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


