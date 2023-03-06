---
title: Class VectorShapeTransform
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeTransform sınıf. Vektör şekli dönüştürme matrisini tanımlar class
type: docs
weight: 1460
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/
---
## VectorShapeTransform class

Vektör şekli dönüştürme matrisini tanımlar class

```csharp
public sealed class VectorShapeTransform
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [VectorShapeTransform](vectorshapetransform/)() | Yeni bir örneğini başlatır.`VectorShapeTransform` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Tx](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/tx/) { get; set; } | TX değerini alır veya ayarlar. |
| [Ty](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/ty/) { get; set; } | TY değerini alır veya ayarlar. |
| [Xx](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/xx/) { get; set; } | XX değerini alır veya ayarlar. |
| [Xy](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/xy/) { get; set; } | XY değerini alır veya ayarlar. |
| [Yx](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/yx/) { get; set; } | YX değerini alır veya ayarlar. |
| [Yy](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/yy/) { get; set; } | YY değerini alır veya ayarlar. |

### Örnekler

Aşağıdaki kod, vektör yolları içeren bir şekil katmanlarını yeniden boyutlandırma yeteneğini gösterir.

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Bu örnek, PSD dosyasındaki FillLayer'ın Vogk kaynağındaki ShapeOriginSettings'in yeni Transform ve OriginBoxCorners özelliklerinin nasıl alınacağını ve ayarlanacağını gösterir.

```csharp
[C#]

// Bu örnek, yeni Transform ve OriginBoxCorners özelliklerinin nasıl alınacağını ve ayarlanacağını gösterir
// PSD dosyasındaki FillLayer'ın Vogk kaynağındaki ShapeOriginSettings'in
string sourceFileName = "vectorShape_25_50.psd";
string outputPath = "result.psd";

VectorShapeOriginSettings originalSetting;
const int layerIndex = 0;

// Orijinal görüntüyü yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    AssertIsTrue(layerIndex < image.Layers.Length);
    var layer = image.Layers[layerIndex];
    AssertIsTrue(layer is FillLayer);
    var resource = GetVogkResource((FillLayer)layer);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);

    // Okuduktan sonra onayla
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(5, setting.OriginType);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(Rectangle.FromLeftTopRightBottom(3, 7, 10, 22), setting.OriginShapeBox.Bounds);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(300d, setting.OriginResolution);

    // yeni özellikleri onayla
    AssertAreEqual(true, setting.IsTransformPresent);
    AssertAreEqual(0d, setting.Transform.Tx);
    AssertAreEqual(0d, setting.Transform.Ty);
    AssertAreEqual(0.050000000000000003d, setting.Transform.Xx);
    AssertAreEqual(0d, setting.Transform.Yx);
    AssertAreEqual(0d, setting.Transform.Xy);
    AssertAreEqual(0.1d, setting.Transform.Yy);
    AssertAreEqual(true, setting.IsOriginBoxCornersPresent);
    AssertAreEqual(2.9000000000000004d, setting.OriginBoxCorners[0]);
    AssertAreEqual(7.3000000000000007d, setting.OriginBoxCorners[1]);
    AssertAreEqual(10.450000000000001d, setting.OriginBoxCorners[2]);
    AssertAreEqual(7.3000000000000007d, setting.OriginBoxCorners[3]);
    AssertAreEqual(10.450000000000001d, setting.OriginBoxCorners[4]);
    AssertAreEqual(22.400000000000002d, setting.OriginBoxCorners[5]);
    AssertAreEqual(2.9000000000000004d, setting.OriginBoxCorners[6]);
    AssertAreEqual(22.400000000000002d, setting.OriginBoxCorners[7]);

    // yeni özellikler ayarla
    originalSetting = resource.ShapeOriginSettings[0];
    originalSetting.Transform.Tx = 0.2d;
    originalSetting.Transform.Ty = 0.3d;
    originalSetting.Transform.Xx = 0.4d;
    originalSetting.Transform.Xy = 0.5d;
    originalSetting.Transform.Yx = 0.6d;
    originalSetting.Transform.Yy = 0.7d;
    originalSetting.OriginBoxCorners = new double[8] { 9, 8, 7, 6, 5, 4, 3, 2 };

    // Bu PSD görüntüsünü değiştirilen özelliklerle kaydedin.
    image.Save(outputPath, new PsdOptions(image));
}

// Kaydedilen PSD görüntüsünü değiştirilen özelliklerle yükleyin.
using (PsdImage image = (PsdImage)Image.Load(outputPath))
{
    var layer = image.Layers[layerIndex];
    AssertIsTrue(layer is FillLayer);
    var resource = GetVogkResource((FillLayer)layer);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);

    // Özelliklerin doğru kaydedildiğini ve yüklendiğini onaylayın 
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsTransformPresent);
    AssertAreEqual(0.2d, setting.Transform.Tx);
    AssertAreEqual(0.3d, setting.Transform.Ty);
    AssertAreEqual(0.4d, setting.Transform.Xx);
    AssertAreEqual(0.5d, setting.Transform.Xy);
    AssertAreEqual(0.6d, setting.Transform.Yx);
    AssertAreEqual(0.7d, setting.Transform.Yy);
    AssertAreEqual(true, setting.IsOriginBoxCornersPresent);
    AssertAreEqual(originalSetting.OriginBoxCorners[0], setting.OriginBoxCorners[0]);
    AssertAreEqual(originalSetting.OriginBoxCorners[1], setting.OriginBoxCorners[1]);
    AssertAreEqual(originalSetting.OriginBoxCorners[2], setting.OriginBoxCorners[2]);
    AssertAreEqual(originalSetting.OriginBoxCorners[3], setting.OriginBoxCorners[3]);
    AssertAreEqual(originalSetting.OriginBoxCorners[4], setting.OriginBoxCorners[4]);
    AssertAreEqual(originalSetting.OriginBoxCorners[5], setting.OriginBoxCorners[5]);
    AssertAreEqual(originalSetting.OriginBoxCorners[6], setting.OriginBoxCorners[6]);
    AssertAreEqual(originalSetting.OriginBoxCorners[7], setting.OriginBoxCorners[7]);
}

VogkResource GetVogkResource(FillLayer layer)
{
    if (layer == null)
    {
        throw new PsdImageArgumentException("The parameter layer should not be null.");
    }

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new PsdImageException("VogkResource not found.");
    }

    return resource;
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}
```

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* toplantı [Aspose.PSD](../../)


