---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "FontSettings-methode. Verwijdert het lettertypecachebestand."
type: docs
weight: 100
url: /nl/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Verwijdert het lettertypecachebestand.

```csharp
public static void RemoveFontCacheFile()
```

## Voorbeelden

De volgende code toont de methode voor het verwijderen van het bestand met de cache van geladen lettertypen.

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

### Zie ook

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


