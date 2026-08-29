---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo FontSettings. Rimuove il file della cache dei font"
type: docs
weight: 100
url: /it/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Rimuove il file della cache dei font.

```csharp
public static void RemoveFontCacheFile()
```

## Esempi

Il codice seguente dimostra il metodo per rimuovere il file con la cache dei font caricati.

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

### Vedi anche

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


