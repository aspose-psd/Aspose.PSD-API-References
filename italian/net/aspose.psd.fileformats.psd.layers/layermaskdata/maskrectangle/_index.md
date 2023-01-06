---
title: MaskRectangle
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Ottiene o imposta la mascheraRectangleaspose.psd/rectangledella maschera di livello nel file PSD. Prende le proprietà sinistra destra alto e basso e creaRectangleaspose.psd/rectangle
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Ottiene o imposta la maschera[`Rectangle`](../../../aspose.psd/rectangle)della maschera di livello nel file PSD. Prende le proprietà sinistra, destra, alto e basso e crea[`Rectangle`](../../../aspose.psd/rectangle)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Valore della proprietà

Il rettangolo della maschera.

### Esempi

Questo esempio mostra come ottenere, aggiornare, rimuovere e aggiungere maschere di livello raster nel file Adobe® Photoshop® a livello di codice.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

string dataDir = "PSDNET640_1" + Path.DirectorySeparatorChar;

// Ottiene il valore int convertito in ordine di byte big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Ottiene il valore convertito dal big endian a Int32.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// Ottiene una maschera raster dal livello di un'immagine PSD e la salva in un file
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// Aggiunge una maschera raster dal file al livello e la salva nell'immagine in formato PSD
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // La semplice aggiunta di LayerMaskData non è sufficiente per il corretto salvataggio perché i canali non vengono aggiornati;
    // layer.LayerMaskData = maschera; // Questo non aggiunge il canale maschera

    // Aggiungi (o aggiorna) la maschera
    layer.AddLayerMask(maskData); // Ma questo aggiunge / aggiorna sia la maschera che i canali!
}

// Questo esempio mostra come ottenere, aggiornare, rimuovere e aggiungere maschere di livello raster nel file Adobe® Photoshop® a livello di codice.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
Directory.CreateDirectory(dataDir);
var sourceFilePath = dataDir + "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Ottieni una maschera raster dal livello e salvala in un file
    SaveRasterMask(dataDir + "FourWithMasks2.msk", layer);

    // Cambia la maschera di livello (inverti) e salva l'immagine
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Basta cambiare LayerMaskData per effettuare il rendering
    image.Save(dataDir + "FourWithMasksUpdated2.png", pngOptions);

    // Ma la semplice modifica di LayerMaskData non è sufficiente per il corretto salvataggio perché i canali non vengono aggiornati;
    layer.LayerMaskData = mask; // Neanche questo funziona
    layer.AddLayerMask(mask); // Ma questo aggiorna sia la maschera che i canali!
    image.Save(dataDir + "FourWithMasksUpdated2.psd");

    // Rimuovi una maschera raster dal livello e salva l'immagine
    layer.LayerMaskData = null; // La semplice rimozione di LayerMaskData è sufficiente per effettuare il rendering ma non per il salvataggio in formato PSD
    image.Save(dataDir + "FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Ma questo rimuove sia la maschera che il canale della maschera!
    image.Save(dataDir + "FourWithMasksRemoved2.psd");

    // Aggiungi una maschera raster dal file al livello e salva l'immagine
    AddRasterMask(layer, dataDir + "raster.msk");
    image.Save(dataDir + "FourWithMasksAdded2.png", pngOptions);
    image.Save(dataDir + "FourWithMasksAdded2.psd");
}
```

### Guarda anche

* struct [Rectangle](../../../aspose.psd/rectangle)
* class [LayerMaskData](../../layermaskdata)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
