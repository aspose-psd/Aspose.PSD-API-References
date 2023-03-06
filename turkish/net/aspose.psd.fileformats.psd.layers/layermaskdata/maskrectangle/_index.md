---
title: LayerMaskData.MaskRectangle
second_title: Aspose.PSD for .NET API Referansı
description: LayerMaskData mülk. Maskeyi alır veya ayarlarRectanglePSD dosyasındaki katman maskesinin. Left right top ve bottom özelliklerini alır ve oluştururRectangle
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Maskeyi alır veya ayarlar[`Rectangle`](../../../aspose.psd/rectangle/)PSD dosyasındaki katman maskesinin. Left, right, top ve bottom özelliklerini alır ve oluşturur[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Mülk değeri

Maske dikdörtgeni.

### Örnekler

Bu örnek, Adobe® Photoshop® dosyasındaki raster katman maskelerinin program aracılığıyla nasıl alınacağını, güncelleneceğini, kaldırılacağını ve ekleneceğini gösterir.

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

// big-endian bayt sırasına dönüştürülen int değerini alır.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Büyük endian'dan Int32'ye dönüştürülen değeri alır.
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

// Bir PSD görüntüsünün katmanından bir tarama maskesi alır ve bunu bir dosyaya kaydeder
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

// Dosyadan katmana bir tarama maskesi ekler ve onu PSD formatındaki görüntü olarak kaydeder
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

    // Kanallar güncellenmediği için sadece LayerMaskData eklemek doğru kayıt için yeterli değildir;
    // katman.LayerMaskData = maske; // Bu, maske kanalını eklemez

    // Maskeyi ekleyin (veya güncelleyin)
    layer.AddLayerMask(maskData); // Ancak bu, hem maskeyi hem de kanalları ekler / günceller!
}

// Bu örnek, Adobe® Photoshop® dosyasındaki raster katman maskelerinin program aracılığıyla nasıl alınacağını, güncelleneceğini, kaldırılacağını ve ekleneceğini gösterir.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Katmandan bir tarama maskesi alın ve bunu bir dosyaya kaydedin
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Katman maskesini değiştirin (ters çevirin) ve görüntüyü kaydedin
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Yalnızca LayerMaskData'yı değiştirmek, işlemeyi etkilemek için yeterlidir
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Ama sadece LayerMaskData'yı değiştirmek doğru kayıt için yeterli değil çünkü kanallar güncellenmiyor;
    layer.LayerMaskData = mask; // Bu da çalışmıyor
    layer.AddLayerMask(mask); // Ancak bu hem maskeyi hem de kanalları günceller!
    image.Save("FourWithMasksUpdated2.psd");

    // Katmandan bir tarama maskesini kaldırın ve görüntüyü kaydedin
    layer.LayerMaskData = null; // Yalnızca LayerMaskData'yı kaldırmak, işlemeyi etkilemek için yeterlidir, ancak PSD formatına kaydetmek için yeterli değildir
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Ancak bu hem maskeyi hem de maske kanalını kaldırır!
    image.Save("FourWithMasksRemoved2.psd");

    // Dosyadan katmana bir tarama maskesi ekleyin ve görüntüyü kaydedin
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* toplantı [Aspose.PSD](../../../)


