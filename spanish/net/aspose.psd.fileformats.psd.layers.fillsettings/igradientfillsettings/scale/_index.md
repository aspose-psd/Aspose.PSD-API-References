---
title: "IGradientFillSettings.Scale"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad IGradientFillSettings. Obtiene o establece la escala de degradado normalizada en porcentaje"
type: docs
weight: 90
url: /es/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Obtiene o establece la escala de degradado **normalizada** (en porcentaje).

```csharp
public int Scale { get; set; }
```

### Property Value

La escala.

## Ejemplos

El siguiente ejemplo muestra cómo usar la propiedad Scale para escalar FillLayer con un degradado.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // obteniendo una capa de relleno
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // actualizar el valor de escala
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ver también

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


