---
title: SmartObjectLayer.ExportContents
second_title: Aspose.PSD for .NET API 参考
description: SmartObjectLayer 方法. 将嵌入或链接的内容导出到文件
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/
---
## SmartObjectLayer.ExportContents method

将嵌入或链接的内容导出到文件。

```csharp
public void ExportContents(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 导出文件路径。 |

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


