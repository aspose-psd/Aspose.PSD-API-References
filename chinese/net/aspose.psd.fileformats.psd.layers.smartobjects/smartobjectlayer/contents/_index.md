---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD for .NET API 参考
description: SmartObjectLayer 财产. 获取或设置智能对象图层内容 嵌入的智能对象内容为嵌入的原始图像文件Data及其属性 链接的智能对象内容是链接图像文件的原始内容如果可用及其属性LiFeDataSource . 我们不支持从 Adobe. Photoshop. . 图形库加载时IsLibraryLink是真的 对于常规链接文件首先我们使用RelativePath在源图像路径中查找文件 relatively SourceImagePath  如果不可用我们看看FullPath 如果不是那么我们在图像所在的同一目录中查找链接文件SourceImagePath .
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

获取或设置智能对象图层内容。 嵌入的智能对象内容为嵌入的原始图像文件：[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/)及其属性。 链接的智能对象内容是链接图像文件的原始内容（如果可用）及其属性：[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . 我们不支持从 Adobe. Photoshop. . 图形库加载时[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/)是真的。 对于常规链接文件，首先，我们使用[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/)在源图像路径中查找文件 relatively SourceImagePath , 如果不可用我们看看[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), 如果不是，那么我们在图像所在的同一目录中查找链接文件：SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### 适当的价值

的byte[]智能对象层内容.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| NotSupportedException | 无法从 Adobe® Photoshop® 库中获取内容。 |

### 例子

以下代码演示了对嵌入式智能对象的支持。

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// 此示例演示如何更改 PSD 文件中的智能对象层以及导出/更新智能对象原始嵌入内容。
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

        // 让我们从 PSD 智能对象层导出嵌入的智能对象图像
        smartObjectLayer.ExportContents(exportPath);

        // 让我们检查原始图像是否正确保存
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // 让我们反转原始智能对象图像
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // 让我们替换 PSD 层中嵌入的智能对象图像
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 让我们检查更新的图像是否正确保存
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 也可以看看

* class [SmartObjectLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* 部件 [Aspose.PSD](../../../)


