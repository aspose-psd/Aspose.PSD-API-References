---
title: "Sınıf BaseFxResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseFxResource sınıfı. Temel efektler kaynağı"
type: docs
weight: 2550
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/basefxresource/
---
{{< psd/tize >}}
## BaseFxResource class

Temel efekt kaynağı

```csharp
public abstract class BaseFxResource : LayerResource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Tanımlayıcı sürümünü alır. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Örnekler

Aşağıdaki kod çoklu efekt kaynağının desteğini gösterir.

```csharp
[C#]

// PSD görüntüsü 2 Drop Shadow efekti içerir
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // PSD görüntüsünü 2 Drop Shadow efektiyle render eder
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // Üçüncü bir Drop Shadow efekti ekler.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // PSD görüntüsünü 3 Drop Shadow efektiyle render eder
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Katman aynı türde birden fazla efekt içeriyorsa imfx kaynağı kullanılır.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // Tüm efektleri temizler.
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // PSD görüntüsünü 1 Drop Shadow efektiyle render eder (diğerleri silindi).
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Katman aynı türde birden fazla efekt içermiyorsa lfx2 kaynağı kullanılır.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


