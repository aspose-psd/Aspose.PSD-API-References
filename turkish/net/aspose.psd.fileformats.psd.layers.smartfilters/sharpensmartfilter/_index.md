---
title: "SharpenSmartFilter sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter sınıfı. Keskinleştirme akıllı filtresi"
type: docs
weight: 3890
url: /tr/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Sharpen akıllı filtresi.

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | `SharpenSmartFilter` sınıfının yeni bir örneğini başlatır. |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | `SharpenSmartFilter` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Karıştırma modunu alır veya ayarlar. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | Akıllı filtre türü tanımlayıcısını alır. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Akıllı filtrenin etkin olup olmadığını alır veya ayarlar. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | Akıllı filtre adını alır. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Akıllı filtrenin opaklık değerini alır veya ayarlar. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Akıllı filtre verileri içeren kaynak tanımlayıcı yapısı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Geçerli filtreyi giriş [`RasterImage`](../../aspose.psd/rasterimage/) görüntüsüne uygular. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Geçerli filtreyi giriş [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) maske verilerine uygular. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Türün geçerli örneğinin üye bazlı klonunu oluşturur. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | Geçerli akıllı filtrenin tanımlayıcısı. |

## Örnekler

Aşağıdaki kod SharpenSmartFilter desteğini gösterir.

```csharp
[C#]

string sourceFile = "sharpen_source.psd";
string outputPsd = "sharpen_output.psd";
string outputPng = "sharpen_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // akıllı filtreleri düzenle
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // filtre değerlerini kontrol et
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // filtre değerlerini güncelle
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // yeni filtre öğeleri ekle
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // değişiklikleri uygula
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Ayrıca Bakınız

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


