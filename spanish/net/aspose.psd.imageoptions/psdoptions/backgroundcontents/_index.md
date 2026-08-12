---
title: "PsdOptions.BackgroundContents"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PsdOptions. Obtiene o establece el color del fondo. Se puede ver bajo objetos transparentes"
type: docs
weight: 20
url: /es/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Obtiene o establece el color de fondo. Se puede ver bajo objetos transparentes.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Ejemplos

El siguiente código demuestra el soporte de la propiedad BackgroundContents en PsdOptions.

```csharp
[C#]

// La semitransparencia se procesa incorrectamente en la vista previa del archivo psd.
// BackgroundContents asignado a Blanco. Las áreas transparentes deben tener color blanco.

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### Ver también

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


