---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdOptions. Obtient ou définit la couleur de l'arrière-plan. Elle peut être vue sous les objets transparents"
type: docs
weight: 20
url: /fr/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Obtient ou définit la couleur d'arrière-plan. Elle peut être vue sous les objets transparents.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Exemples

Le code suivant montre la prise en charge de la propriété BackgroundContents dans PsdOptions.

```csharp
[C#]

// La semi-transparence est mal traitée dans l'aperçu du fichier psd.
// BackgroundContents assigné à Blanc. Les zones transparentes doivent être de couleur blanche.

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

### Voir aussi

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


