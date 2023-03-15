---
title: Class SmartFilter
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SmartFilter कक्ष. स्मर्ट फ़ल्टर के आधर तर्क क संसधत करने के लए वर्ग
type: docs
weight: 3460
url: /hi/net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---
## SmartFilter class

स्मार्ट फ़िल्टर के आधार तर्क को संसाधित करने के लिए वर्ग।

```csharp
public abstract class SmartFilter : ICloneable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SmartFilter](smartfilter/)() | का एक नया उदाहरण प्रारंभ करता है`SmartFilter` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | सम्मिश्रण मोड प्राप्त या सेट करता है। |
| abstract [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/filterid/) { get; } | स्मार्ट फ़िल्टर प्रकार पहचानकर्ता प्राप्त करता है। |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त या सेट करता है। |
| abstract [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/name/) { get; } | स्मार्ट फ़िल्टर नाम प्राप्त करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | स्मार्ट फ़िल्टर का अपारदर्शिता मान प्राप्त या सेट करता है। |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | स्मार्ट फ़िल्टर डेटा के साथ स्रोत डिस्क्रिप्टर संरचना। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | वर्तमान फ़िल्टर को इनपुट पर लागू करता है[`RasterImage`](../../aspose.psd/rasterimage/) छवि. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | वर्तमान फ़िल्टर को इनपुट पर लागू करता है[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) मास्क डेटा. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | प्रकार के वर्तमान उदाहरण का सदस्यवार क्लोन बनाता है। |

### उदाहरण

यह उदाहरण स्मार्ट फ़िल्टर इंटरफ़ेस के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // स्मार्ट फिल्टर संपादित करें
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // फ़िल्टर मानों की जाँच करें
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // अद्यतन फ़िल्टर मान
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // नए फ़िल्टर आइटम जोड़ें
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // परिवर्तनों को लागू करें
    smartObj.SmartFilters.UpdateResourceValues();

    // फ़िल्टर लागू करें
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // फ़िल्टर मानों की जाँच करें
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* सभा [Aspose.PSD](../../)


