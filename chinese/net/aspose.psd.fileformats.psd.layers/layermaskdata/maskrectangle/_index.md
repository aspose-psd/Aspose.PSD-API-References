---
title: MaskRectangle
second_title: Aspose.PSD for .NET API 参考
description: 获取或设置掩码Rectangleaspose.psd/rectanglePSD 文件中的图层蒙版 它采用左右顶部和底部属性并创建Rectangleaspose.psd/rectangle
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

获取或设置掩码[`Rectangle`](../../../aspose.psd/rectangle)PSD 文件中的图层蒙版。 它采用左、右、顶部和底部属性并创建[`Rectangle`](../../../aspose.psd/rectangle)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### 适当的价值

蒙版矩形。

### 例子

此示例说明如何以编程方式在 Adobe® Photoshop® 文件中获取、更新、删除和添加光栅图层蒙版。

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

// 获取转换为大端字节顺序的 int 值。
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// 获取从大端转换为 Int32 的值。
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

// 从 PSD 图像的图层中获取光栅蒙版并将其保存到文件中
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

// 将文件中的光栅蒙版添加到图层并将其保存为 PSD 格式的图像
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

    // 仅添加 LayerMaskData 不足以正确保存，因为通道没有更新；
    // layer.LayerMaskData = mask; // 这不会添加遮罩通道

    // 添加（或更新）掩码
    layer.AddLayerMask(maskData); // 但这会添加/更新掩码和通道！
}

// 此示例说明如何以编程方式在 Adobe® Photoshop® 文件中获取、更新、删除和添加光栅图层蒙版。
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
Directory.CreateDirectory(dataDir);
var sourceFilePath = dataDir + "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // 从图层中获取光栅蒙版并将其保存到文件中
    SaveRasterMask(dataDir + "FourWithMasks2.msk", layer);

    //更改图层蒙版（反转）并保存图像
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // 仅仅改变 LayerMaskData 就足以影响渲染
    image.Save(dataDir + "FourWithMasksUpdated2.png", pngOptions);

    // 但是仅仅改变 LayerMaskData 是不足以正确保存的，因为通道没有更新；
    layer.LayerMaskData = mask; // 这也不起作用
    layer.AddLayerMask(mask); // 但这会同时更新遮罩和通道！
    image.Save(dataDir + "FourWithMasksUpdated2.psd");

    // 从图层中移除光栅蒙版并保存图像
    layer.LayerMaskData = null; // 仅删除 LayerMaskData 就足以影响渲染，但不能保存为 PSD 格式
    image.Save(dataDir + "FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // 但这会同时移除遮罩和遮罩通道！
    image.Save(dataDir + "FourWithMasksRemoved2.psd");

    // 将文件中的光栅蒙版添加到图层并保存图像
    AddRasterMask(layer, dataDir + "raster.msk");
    image.Save(dataDir + "FourWithMasksAdded2.png", pngOptions);
    image.Save(dataDir + "FourWithMasksAdded2.psd");
}
```

### 也可以看看

* struct [Rectangle](../../../aspose.psd/rectangle)
* class [LayerMaskData](../../layermaskdata)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
