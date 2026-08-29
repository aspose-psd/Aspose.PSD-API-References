---
title: "क्लास PixelsData"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.PixelsData क्लास। इमेज पिक्सेल डेटा और उसके बाउंड्स को संग्रहीत करने के लिए क्लास"
type: docs
weight: 5740
url: /hi/net/aspose.psd/pixelsdata/
---
{{< psd/tize >}}
## PixelsData class

छवि पिक्सेल डेटा और उसकी सीमाओं को संग्रहीत करने के लिए क्लास।

```csharp
public sealed class PixelsData : ICloneable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | `PixelsData` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | `PixelsData` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | पिक्सेल डेटा के बाउंड्स को प्राप्त करता है या सेट करता है। |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | पिक्सेल डेटा को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Clone](../../aspose.psd/pixelsdata/clone/)() | यह इंस्टेंस की पूरी कॉपी बनाता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक कस्टम रेंडरर वाला कस्टम स्मार्ट फ़िल्टर बनाया जाए।

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // इनपुट एरे पर असमर्थित 'Crystallize' स्मार्ट फ़िल्टर को इनिट करता है।
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Crystallize' स्मार्ट फ़िल्टर आईडी।
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

        // लेयर मास्क पर फ़िल्टर लागू करें
        smartFilter.ApplyToMask(maskLayer);

        //लेयर पर फ़िल्टर लागू करें
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
        // 'Crystallize' स्मार्ट फ़िल्टर आईडी।
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // फ़िल्टर संरचना प्राप्त करें
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Crystallize आकार का मान प्राप्त करें
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

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


