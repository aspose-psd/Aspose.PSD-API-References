---
title: IGradientFillSettings.Scale
second_title: Referencia de API de Aspose.PSD para .NET
description: IGradientFillSettings propiedad. Obtiene o establece la escala.
type: docs
weight: 100
url: /es/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Obtiene o establece la escala.

```csharp
public int Scale { get; set; }
```

### El valor de la propiedad

La báscula.

### Ejemplos

El siguiente ejemplo muestra cómo usar la propiedad Scale para escalar FillLayer con degradado.

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

    // actualizar valor de escala
    settings.Scale = 200;
    fillLayer.Update(); // Actualiza los datos de píxeles

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ver también

* interface [IGradientFillSettings](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* asamblea [Aspose.PSD](../../../)


