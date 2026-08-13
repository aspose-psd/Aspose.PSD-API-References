---
title: "BlwhResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BlwhResource sınıfı. BlwhResource sınıfı, Siyah ve Beyaz Ayarlama Katmanı'nın bir kaynağıdır."
type: docs
weight: 2580
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---
{{< psd/tize >}}
## BlwhResource class

BlwhResource sınıfı, Siyah ve Beyaz Ayarlama Katmanı'nın bir kaynağıdır.

```csharp
public class BlwhResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BlwhResource](blwhresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlackAndWhitePresetFileName](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blackandwhitepresetfilename/) { get; set; } | Siyah ve Beyaz ön ayar dosya adını alır veya ayarlar. |
| [Blues](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blues/) { get; set; } | Mavi değerini alır veya ayarlar. |
| [BwPresetKind](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/bwpresetkind/) { get; set; } | Siyah ve Beyaz ön ayar tür değerini alır veya ayarlar. |
| [Cyans](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/cyans/) { get; set; } | Camgöbeği değerini alır veya ayarlar. |
| [Greens](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/greens/) { get; set; } | Yeşil değerini alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [Magentas](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/magentas/) { get; set; } | Macenta değerini alır veya ayarlar. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| [Reds](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/reds/) { get; set; } | Kırmızı değerini alır veya ayarlar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [TintColor](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/tintcolor/) { get; set; } | Tint Renk ARGB değerini alır veya ayarlar. |
| [UseTint](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/usetint/) { get; set; } | Bir değeri alır veya ayarlar; bu değer [tint color] kullanılıp kullanılmadığını gösterir. |
| [Yellows](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/yellows/) { get; set; } | Sarı değerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki örnek, bir BlwhResource'ı nasıl düzenleyeceğinizi gösterir.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

const string ActualPropertyValueIsWrongMessage = "Expected property value is not equal to actual value";

string destinationFileName = "Output" + sourceFileName;
bool isRequiredResourceFound = false;
using (PsdImage im = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == tintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == bwPresetKind, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == bwPresetFileName, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue) < 1e-6, ActualPropertyValueIsWrongMessage);

                // Düzenleme ve kaydetme testi
                blwhResource.Reds = reds - 15;
                blwhResource.Yellows = yellows - 15;
                blwhResource.Greens = greens + 15;
                blwhResource.Cyans = cyans + 15;
                blwhResource.Blues = blues - 15;
                blwhResource.Magentas = magentas - 15;
                blwhResource.UseTint = !useTint;
                blwhResource.BwPresetKind = 4;
                blwhResource.BlackAndWhitePresetFileName = "bwPresetFileName";
                blwhLayer.TintColorRed = tintColorRed - 60;
                blwhLayer.TintColorGreen = tintColorGreen - 60;
                blwhLayer.TintColorBlue = tintColorBlue - 60;

                im.Save(destinationFileName);
                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");

isRequiredResourceFound = false;

using (PsdImage im = (PsdImage)Image.Load(destinationFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == !useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == newTintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == 4, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == "bwPresetFileName", ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue + 60) < 1e-6, ActualPropertyValueIsWrongMessage);

                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");
```

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


