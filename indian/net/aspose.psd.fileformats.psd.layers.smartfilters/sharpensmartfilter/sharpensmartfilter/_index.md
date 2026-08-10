---
title: "SharpenSmartFilter.SharpenSmartFilter"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "SharpenSmartFilter कंस्ट्रक्टर. SharpenSmartFilter क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter() {#constructor}

[`SharpenSmartFilter`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public SharpenSmartFilter()
```

## उदाहरण

निम्नलिखित कोड SharpenSmartFilter के समर्थन को दर्शाता है।

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

    // स्मार्ट फ़िल्टर संपादित करें
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // फ़िल्टर मान जाँचें
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // फ़िल्टर मान अपडेट करें
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // नए फ़िल्टर आइटम जोड़ें
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // परिवर्तनों को लागू करें
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### देखें भी

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)

---

## SharpenSmartFilter(DescriptorStructure) {#constructor_1}

[`SharpenSmartFilter`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public SharpenSmartFilter(DescriptorStructure sourceDescriptor)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceDescriptor | DescriptorStructure | स्मार्ट फ़िल्टर जानकारी के साथ डिस्क्रिप्टर संरचना। |

### देखें भी

* class [DescriptorStructure](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/)
* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


