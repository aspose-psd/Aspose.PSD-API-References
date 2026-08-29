---
title: "PsdOptions.BackgroundContents"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà PsdOptions. Ottiene o imposta il colore di sfondo. Può essere visto sotto gli oggetti trasparenti"
type: docs
weight: 20
url: /it/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Ottiene o imposta il colore di sfondo. Può essere visto sotto gli oggetti trasparenti.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Esempi

Il codice seguente dimostra il supporto della proprietà BackgroundContents in PsdOptions.

```csharp
[C#]

// La semitrasparenza è elaborata in modo errato nell'anteprima del file psd.
// BackgroundContents assegnato a White. Le aree trasparenti dovrebbero avere colore bianco.

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

### Vedi anche

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


