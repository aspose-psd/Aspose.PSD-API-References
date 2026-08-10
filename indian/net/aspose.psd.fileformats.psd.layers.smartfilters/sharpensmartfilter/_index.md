---
title: "क्लास SharpenSmartFilter"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter क्लास। शार्पन स्मार्ट फ़िल्टर"
type: docs
weight: 3870
url: /hi/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Sharpen स्मार्ट फ़िल्टर।

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | `SharpenSmartFilter` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | `SharpenSmartFilter` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | ब्लेंडिंग मोड प्राप्त करता है या सेट करता है। |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | स्मार्ट फ़िल्टर प्रकार पहचानकर्ता प्राप्त करता है। |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त करता है या सेट करता है। |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | स्मार्ट फ़िल्टर का नाम प्राप्त करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | स्मार्ट फ़िल्टर की अपारदर्शिता मान को प्राप्त करता है या सेट करता है। |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | स्मार्ट फ़िल्टर डेटा के साथ स्रोत वर्णनकर्ता संरचना। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | इनपुट [`RasterImage`](../../aspose.psd/rasterimage/) छवि पर वर्तमान फ़िल्टर लागू करता है। |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | इनपुट [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) मास्क डेटा पर वर्तमान फ़िल्टर लागू करता है। |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | वर्तमान प्रकार की इंस्टेंस की सदस्य-वार क्लोन बनाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | वर्तमान स्मार्ट फ़िल्टर का पहचानकर्ता। |

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

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


