---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD för .NET API‑referens"
description: "FontSettings-metoden. Tar bort teckensnittscache‑filen."
type: docs
weight: 100
url: /sv/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Tar bort teckensnittscache-filen.

```csharp
public static void RemoveFontCacheFile()
```

## Exempel

Följande kod demonstrerar en metod för att ta bort filen med cache för inlästa teckensnitt.

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

### Se även

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


