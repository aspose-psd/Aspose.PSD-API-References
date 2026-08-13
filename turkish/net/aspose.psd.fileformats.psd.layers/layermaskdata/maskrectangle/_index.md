---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerMaskData özelliği. PSD dosyasındaki katman maskesinin maske Rectangle'ını alır veya ayarlar. Sol, sağ, üst ve alt özelliklerini alır ve Rectangle oluşturur."
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

Katman maskesinin maske [`Rectangle`](../../../aspose.psd/rectangle/) değerini alır veya ayarlar. Sol, sağ, üst ve alt özelliklerini alır ve [`Rectangle`](../../../aspose.psd/rectangle/) oluşturur.

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

Maske dikdörtgeni.

## Örnekler

Bu örnek, Adobe® Photoshop® dosyasında raster katman maskelerini programlı olarak alma, güncelleme, kaldırma ve ekleme yöntemlerini gösterir.

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

// Tam sayı değerini büyük‑uçlu bayt sırasına dönüştürerek alır.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Değeri büyük‑uçlu formatından Int32'ye dönüştürerek alır.
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

// Bir PSD görüntüsünün katmanından raster maskeyi alır ve bir dosyaya kaydeder.
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

// Dosyadan bir raster maskeyi katmana ekler ve PSD formatındaki görüntüyü kaydeder.
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

    // Sadece LayerMaskData eklemek, kanallar güncellenmediği için doğru kaydetme için yeterli değildir;
    // layer.LayerMaskData = mask; // Bu maske kanalını eklemez

    // Maskeyi ekle (veya güncelle)
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// Bu örnek, Adobe® Photoshop® dosyasında raster katman maskelerini programlı olarak alma, güncelleme, kaldırma ve ekleme yöntemlerini gösterir.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Katmandan bir raster maskesi al ve bir dosyaya kaydet
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Katman maskesini değiştir (ters çevir) ve resmi kaydet
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Sadece **LayerMaskData**'yi değiştirmek, renderlamayı etkilemek için yeterlidir
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Ancak sadece **LayerMaskData**'yi değiştirmek, kanallar güncellenmediği için doğru kaydetme için yeterli değildir;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // Katmandan bir raster maskesini kaldır ve resmi kaydet
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // Dosyadan bir raster maskesini katmana ekle ve resmi kaydet
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Ayrıca Bakınız

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


