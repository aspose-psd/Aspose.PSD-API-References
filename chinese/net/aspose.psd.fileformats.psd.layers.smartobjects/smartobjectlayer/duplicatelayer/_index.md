---
title: "SmartObjectLayer.DuplicateLayer"
second_title: "Aspose.PSD for .NET API 参考"
description: "SmartObjectLayer 方法。通过复制此对象创建一个新的智能对象图层。请注意，对于嵌入的智能对象，嵌入的图像是共享的。如果想复制嵌入的图像，请使用 NewSmartObjectViaCopy 方法"
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
{{< psd/tize >}}
## SmartObjectLayer.DuplicateLayer method

通过复制此对象创建一个新的智能对象图层。请注意，对于嵌入的智能对象，嵌入的图像是共享的。如果想复制嵌入的图像，请使用 [`NewSmartObjectViaCopy`](../newsmartobjectviacopy/) 方法。

```csharp
public SmartObjectLayer DuplicateLayer()
```

### 返回值

克隆的 [`SmartObjectLayer`](../) 实例。

## 示例

这些示例演示了如何在 PSD 图像中复制智能对象图层。

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// 这些示例演示了如何在 PSD 图像中复制智能对象图层。
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // 让我们反转嵌入的智能对象图像（对于内部 PSD 图像，仅反转其第一图层）
            InvertImage(innerImage);

            // 让我们替换 PSD 图层中的嵌入智能对象图像
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 复制的图层与原始智能对象共享其嵌入的图像
        // 并且应显式更新，否则其渲染缓存保持不变。
        // 我们更新每个智能对象，以确保由 NewSmartObjectViaCopy 创建的新图层
        // 不会与其他图层共享嵌入的图像。
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// 反转光栅图像，包括 PSD 图像。
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// 反转光栅图像。
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### 另请参阅

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


