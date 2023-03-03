---
title: LayerMaskData.MaskRectangle
second_title: Справочник по Aspose.PSD для .NET API
description: LayerMaskData свойство. Получает или устанавливает маскуRectangleмаски слоя в файле PSD. Он принимает левые правые верхние и нижние свойства и создаетRectangle
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Получает или устанавливает маску[`Rectangle`](../../../aspose.psd/rectangle/)маски слоя в файле PSD. Он принимает левые, правые, верхние и нижние свойства и создает[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Стоимость имущества

Прямоугольник маски.

### Примеры

В этом примере показано, как программно получать, обновлять, удалять и добавлять маски растровых слоев в файле Adobe® Photoshop®.

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

// Получает значение int, преобразованное в порядок байтов с обратным порядком байтов.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Получает значение, преобразованное из прямого порядка байтов в Int32.
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

// Получаем растровую маску из слоя PSD-изображения и сохраняем ее в файл
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

// Добавляет растровую маску из файла к слою и сохраняет ее изображение в формате PSD
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

    // Простого добавления LayerMaskData недостаточно для корректного сохранения, т.к. каналы не обновляются;
    // layer.LayerMaskData = маска; // Это не добавляет канал маски

    // Добавляем (или обновляем) маску
    layer.AddLayerMask(maskData); // Но это добавляет/обновляет и маску, и каналы!
}

// В этом примере показано, как программно получать, обновлять, удалять и добавлять маски растровых слоев в файле Adobe® Photoshop®.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Получаем растровую маску из слоя и сохраняем ее в файл
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Изменяем маску слоя (инвертируем) и сохраняем изображение
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Простого изменения LayerMaskData достаточно, чтобы произвести рендеринг
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Но просто изменить LayerMaskData недостаточно для корректного сохранения, т.к. каналы не обновляются;
    layer.LayerMaskData = mask; // Это тоже не работает
    layer.AddLayerMask(mask); // Но при этом обновляются и маска, и каналы!
    image.Save("FourWithMasksUpdated2.psd");

    // Удаляем растровую маску со слоя и сохраняем изображение
    layer.LayerMaskData = null; // Простого удаления LayerMaskData достаточно для рендеринга, но не для сохранения в формате PSD
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Но при этом удаляется и маска, и маскирующий канал!
    image.Save("FourWithMasksRemoved2.psd");

    // Добавляем растровую маску из файла на слой и сохраняем изображение
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Смотрите также

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* сборка [Aspose.PSD](../../../)


