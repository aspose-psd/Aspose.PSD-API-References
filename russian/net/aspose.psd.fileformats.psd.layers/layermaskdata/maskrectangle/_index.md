---
title: "LayerMaskData.MaskRectangle"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство LayerMaskData. Получает или задает прямоугольник маски слоя в файле PSD. Он принимает свойства left, right, top и bottom и создает Rectangle"
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

Получает или задает маску [`Rectangle`](../../../aspose.psd/rectangle/) маски слоя в файле PSD. Он принимает свойства left, right, top и bottom и создает [`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

Прямоугольник маски.

## Примеры

Этот пример показывает, как программно получать, обновлять, удалять и добавлять растровые маски слоёв в файле Adobe® Photoshop®.

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

// Получает целочисленное значение, преобразованное в порядок байтов big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Получает значение, преобразованное из big-endian в Int32.
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

// Получает растровую маску из слоя изображения PSD и сохраняет её в файл
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

// Добавляет растровую маску из файла в слой и сохраняет её в изображении формата PSD
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

    // Просто добавление LayerMaskData недостаточно для корректного сохранения, поскольку каналы не обновляются;
    // layer.LayerMaskData = mask; // Это не добавляет канал маски

    // Добавить (или обновить) маску
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// Этот пример показывает, как программно получать, обновлять, удалять и добавлять растровые маски слоёв в файле Adobe® Photoshop®.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Получить растровую маску из слоя и сохранить её в файл
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Изменить маску слоя (инвертировать) и сохранить изображение
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Просто изменение LayerMaskData достаточно для влияния на рендеринг
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Но простое изменение LayerMaskData недостаточно для корректного сохранения, поскольку каналы не обновляются;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // Удалить растровую маску из слоя и сохранить изображение
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // Добавить растровую маску из файла в слой и сохранить изображение
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### См. также

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


