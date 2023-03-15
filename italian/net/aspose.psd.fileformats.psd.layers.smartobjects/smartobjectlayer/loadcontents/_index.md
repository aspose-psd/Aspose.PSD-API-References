---
title: SmartObjectLayer.LoadContents
second_title: Aspose.PSD per riferimento API .NET
description: SmartObjectLayer metodo. Ottiene il contenuto dellimmagine incorporata o collegata del livello degli oggetti avanzati.
type: docs
weight: 110
url: /it/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/
---
## SmartObjectLayer.LoadContents method

Ottiene il contenuto dell'immagine incorporata o collegata del livello degli oggetti avanzati.

```csharp
public Image LoadContents(LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | LoadOptions | Le opzioni. |

### Valore di ritorno

Il carico[`Image`](../../../aspose.psd/image/) istanza oggetto intelligente.

### Esempi

Il codice seguente illustra il supporto degli oggetti Embedded Smart.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Questo esempio mostra come modificare il livello degli oggetti avanzati nel file PSD ed esportare/aggiornare i contenuti incorporati originali degli oggetti avanzati.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Esportiamo l'immagine dell'oggetto avanzato incorporato dal livello dell'oggetto avanzato PSD
        smartObjectLayer.ExportContents(exportPath);

        // Controlliamo se l'immagine originale è stata salvata correttamente
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Invertiamo l'immagine dell'oggetto intelligente originale
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Sostituiamo l'immagine dell'oggetto smart incorporata nel livello PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Controlliamo se l'immagine aggiornata è stata salvata correttamente
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Guarda anche

* class [Image](../../../aspose.psd/image/)
* class [LoadOptions](../../../aspose.psd/loadoptions/)
* class [SmartObjectLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* assemblea [Aspose.PSD](../../../)


