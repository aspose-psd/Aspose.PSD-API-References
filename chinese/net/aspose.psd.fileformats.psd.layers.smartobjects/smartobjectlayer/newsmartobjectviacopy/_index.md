---
title: SmartObjectLayer.NewSmartObjectViaCopy
second_title: Aspose.PSD for .NET API 参考
description: SmartObjectLayer 方法. 通过复制此图层创建一个新的智能对象层 通过 Adobe Photoshop 的复制功能重现图层  智能对象  新智能对象 请注意它仅对嵌入的智能对象启用因为嵌入的图像也被复制了 如果你想分享嵌入的图像使用DuplicateLayer方法.
type: docs
weight: 120
url: /zh/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
## SmartObjectLayer.NewSmartObjectViaCopy method

通过复制此图层创建一个新的智能对象层。 通过 Adobe Photoshop 的复制功能重现“图层 -&gt; 智能对象 -&gt; 新智能对象”。 请注意，它仅对嵌入的智能对象启用，因为嵌入的图像也被复制了。 如果你想分享嵌入的图像使用[`DuplicateLayer`](../duplicatelayer/)方法.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### 返回值

克隆人[`SmartObjectLayer`](../)实例。

### 例子

这些示例演示了如何在 PSD 图像中复制智能对象层。

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// 这些示例演示了如何在 PSD 图像中复制智能对象层。
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // 要复制的层数
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
            // 让我们反转嵌入的智能对象图像（对于内部 PSD 图像，我们只反转它的第一层）
            InvertImage(innerImage);

            // 让我们替换 PSD 层中嵌入的智能对象图像
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 复制层与原始智能对象共享其嵌入图像
        // 它应该显式更新，否则它的渲染缓存保持不变。
        // 我们更新每个智能对象以确保由 NewSmartObjectViaCopy 创建的新层
        // 不与其他人共享嵌入图像。
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

### 也可以看看

* class [SmartObjectLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* 部件 [Aspose.PSD](../../../)


