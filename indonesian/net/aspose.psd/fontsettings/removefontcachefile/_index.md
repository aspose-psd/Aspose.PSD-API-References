---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode FontSettings. Menghapus file cache font"
type: docs
weight: 100
url: /id/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Menghapus file cache font.

```csharp
public static void RemoveFontCacheFile()
```

## Contoh

Kode berikut menunjukkan metode untuk menghapus file cache font yang dimuat.

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

### Lihat Juga

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


