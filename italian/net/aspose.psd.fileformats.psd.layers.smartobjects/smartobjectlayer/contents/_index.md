---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD per riferimento API .NET
description: SmartObjectLayer proprietà. Ottiene o imposta i contenuti del livello delloggetto avanzato. Il contenuto delloggetto avanzato incorporato è il file di immagine raw incorporatoData e le sue proprietà. Il contenuto delloggetto intelligente collegato è il contenuto non elaborato del file immagine collegato se disponibile e le sue proprietàLiFeDataSource . Non supportiamo il caricamento dalla libreria grafica di Adobe Photoshop  quandoIsLibraryLink è vero. Per i normali file di collegamento allinizio usiamoRelativePath per cercare il file relativamente nel percorso dellimmagine di origineSourceImagePath  se non è disponibile guardiamoFullPath  in caso contrario cerchiamo il file di collegamento nella stessa directory in cui si trova la nostra immagineSourceImagePath .
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Ottiene o imposta i contenuti del livello dell'oggetto avanzato. Il contenuto dell'oggetto avanzato incorporato è il file di immagine raw incorporato:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) e le sue proprietà. Il contenuto dell'oggetto intelligente collegato è il contenuto non elaborato del file immagine collegato se disponibile e le sue proprietà:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Non supportiamo il caricamento dalla libreria grafica di Adobe� Photoshop� �� quando[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) è vero. Per i normali file di collegamento, all'inizio, usiamo[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) per cercare il file relativamente nel percorso dell'immagine di origineSourceImagePath , se non è disponibile guardiamo[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , in caso contrario, cerchiamo il file di collegamento nella stessa directory in cui si trova la nostra immagine:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Valore della proprietà

Ilbyte[] contenuti del livello degli oggetti intelligenti.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotSupportedException | Impossibile ottenere contenuti dalla libreria di Adobe� Photoshop� ��. |

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

* class [SmartObjectLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* assemblea [Aspose.PSD](../../../)


