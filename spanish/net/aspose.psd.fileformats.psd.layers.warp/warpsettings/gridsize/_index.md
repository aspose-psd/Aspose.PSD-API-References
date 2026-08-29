---
title: "WarpSettings.GridSize"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad WarpSettings. Obtiene o establece el tamaño de la cuadrícula de deformación. El valor predeterminado es 1"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Obtiene o establece el tamaño de la cuadrícula warp. El valor predeterminado es 1.

```csharp
public Size GridSize { get; set; }
```

## Ejemplos

El siguiente código demuestra el soporte de la propiedad WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Obtener configuraciones de deformación
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Establecer nuevo tamaño
    // Para Photoshop, el valor puede estar entre 1 y 50 y no se puede guardar el archivo PSD correctamente.
    warpSettings.GridSize = new Size(100, 100);

    // Establecer valor válido
    warpSettings.GridSize = new Size(3, 3);

    // Renderizar archivo de ejemplo con cuadrícula x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Ver también

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


