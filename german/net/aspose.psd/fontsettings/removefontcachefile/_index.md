---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FontSettings-Methode. Entfernt die Schriftarten-Cache‑Datei."
type: docs
weight: 100
url: /de/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Entfernt die Schriftarten-Cache-Datei.

```csharp
public static void RemoveFontCacheFile()
```

## Beispiele

Der folgende Code demonstriert die Methode zum Entfernen der Datei mit dem Cache geladener Schriftarten.

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

### Siehe auch

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


