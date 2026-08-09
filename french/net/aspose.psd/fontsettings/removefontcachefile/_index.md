---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode FontSettings. Supprime le fichier de cache des polices"
type: docs
weight: 100
url: /fr/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Supprime le fichier de cache de police.

```csharp
public static void RemoveFontCacheFile()
```

## Exemples

Le code suivant montre la méthode de suppression du fichier de cache des polices chargées.

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

### Voir aussi

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


