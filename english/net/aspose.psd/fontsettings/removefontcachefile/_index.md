---
title: FontSettings.RemoveFontCacheFile
second_title: Aspose.PSD for .NET API Reference
description: FontSettings method. Removes of the font cache file
type: docs
weight: 100
url: /net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Removes of the font cache file.

```csharp
public static void RemoveFontCacheFile()
```

## Examples

The following code demonstrates method for removing file with cache of loaded fonts.

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

### See Also

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


