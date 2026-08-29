---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "FontSettings method. Elimina el archivo de caché de fuentes"
type: docs
weight: 100
url: /es/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Elimina el archivo de caché de fuentes.

```csharp
public static void RemoveFontCacheFile()
```

## Ejemplos

El siguiente código muestra el método para eliminar el archivo con la caché de fuentes cargadas.

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

### Ver también

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


