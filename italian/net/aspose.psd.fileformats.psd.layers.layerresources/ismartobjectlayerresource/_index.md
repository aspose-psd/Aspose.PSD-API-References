---
title: ISmartObjectLayerResource
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce linterfaccia ISmartObjectLayerResource che contiene informazioni su una risorsa del livello di oggetti intelligenti nel file PSD. È anche uninterfaccia di markup utilizzata per designare sia le risorse vendute che quelle esclusive nelle immagini di Adobe Photoshop.
type: docs
weight: 2520
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/
---
## ISmartObjectLayerResource interface

Definisce l'interfaccia ISmartObjectLayerResource che contiene informazioni su una risorsa del livello di oggetti intelligenti nel file PSD. È anche un'interfaccia di markup utilizzata per designare sia le risorse vendute che quelle esclusive nelle immagini di Adobe® Photoshop®.

```csharp
public interface ISmartObjectLayerResource : IPlacedLayerResource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid) { get; set; } | Ottiene o imposta l'identificatore univoco dei dati di questo livello di oggetti intelligenti nell'immagine PSD. |

### Esempi

Il codice seguente illustra il supporto degli oggetti intelligenti incorporati.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Questo esempio mostra come modificare il livello dell'oggetto intelligente nel file PSD ed esportare/aggiornare i contenuti incorporati originali dell'oggetto intelligente.
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

        // Esportiamo l'immagine dell'oggetto intelligente incorporato dal livello dell'oggetto intelligente PSD
        smartObjectLayer.ExportContents(exportPath);

        // Controlliamo se l'immagine originale è stata salvata correttamente
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Invertiamo l'immagine originale dell'oggetto intelligente
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Sostituiamo l'immagine dell'oggetto intelligente incorporato nel livello PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Controlliamo se l'immagine aggiornata è stata salvata correttamente
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Guarda anche

* interface [IPlacedLayerResource](../iplacedlayerresource)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->