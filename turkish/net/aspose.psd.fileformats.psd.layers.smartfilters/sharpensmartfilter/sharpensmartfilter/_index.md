---
title: "SharpenSmartFilter.SharpenSmartFilter"
second_title: "Aspose.PSD for .NET API Referansı"
description: "SharpenSmartFilter yapıcı. SharpenSmartFilter sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter() {#constructor}

[`SharpenSmartFilter`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public SharpenSmartFilter()
```

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

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)

---

## SharpenSmartFilter(DescriptorStructure) {#constructor_1}

[`SharpenSmartFilter`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public SharpenSmartFilter(DescriptorStructure sourceDescriptor)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceDescriptor | DescriptorStructure | Akıllı filtre bilgileri içeren tanımlayıcı yapı. |

### Ayrıca Bakınız

* class [DescriptorStructure](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/)
* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


