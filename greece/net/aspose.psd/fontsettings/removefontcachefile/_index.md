---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος FontSettings. Αφαιρεί το αρχείο cache γραμματοσειρών."
type: docs
weight: 100
url: /el/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Αφαιρεί το αρχείο προσωρινής μνήμης γραμματοσειρών.

```csharp
public static void RemoveFontCacheFile()
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη μέθοδο για την αφαίρεση του αρχείου cache των φορτωμένων γραμματοσειρών.

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

### Δείτε επίσης

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


