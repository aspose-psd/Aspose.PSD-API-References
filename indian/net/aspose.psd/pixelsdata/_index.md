---
title: Class PixelsData
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.PixelsData कक्ष. छव पक्सेल डेट और इसक समओं क संग्रहत करने वल वर्ग
type: docs
weight: 5250
url: /hi/net/aspose.psd/pixelsdata/
---
## PixelsData class

छवि पिक्सेल डेटा और इसकी सीमाओं को संग्रहीत करने वाला वर्ग।

```csharp
public sealed class PixelsData
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`PixelsData` वर्ग. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | का एक नया उदाहरण प्रारंभ करता है`PixelsData` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | पिक्सल डेटा की सीमा प्राप्त या सेट करता है। |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | पिक्सेल डेटा प्राप्त या सेट करता है। |

### उदाहरण

निम्न कोड आपको दिखाता है कि कस्टम रेंडरर वाला कस्टम स्मार्ट फ़िल्टर कैसे बनाया जाए।

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // इनपुट ऐरे पर असमर्थित 'क्रिस्टलाइज़' स्मार्ट फ़िल्टर शुरू करता है
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'क्रिस्टलाइज़' स्मार्ट फ़िल्टर आईडी।
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // SmartObject पर फ़िल्टर लागू करें
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // लेयर मास्क पर फिल्टर लगाएं
        smartFilter.ApplyToMask(maskLayer);

        // परत पर फ़िल्टर लागू करें
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // 'क्रिस्टलाइज़' स्मार्ट फ़िल्टर आईडी।
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // फ़िल्टर संरचना प्राप्त करें
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // क्रिस्टलाइज़ आकार का मान प्राप्त करें
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


