---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FontSettings yöntemi. Yazı tipi önbellek dosyasını kaldırır."
type: docs
weight: 100
url: /tr/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Yazı tipi önbellek dosyasını kaldırır.

```csharp
public static void RemoveFontCacheFile()
```

## Örnekler

Aşağıdaki kod, yüklü yazı tiplerinin önbellek dosyasını kaldırma yöntemini gösterir.

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

### Ayrıca Bakınız

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


