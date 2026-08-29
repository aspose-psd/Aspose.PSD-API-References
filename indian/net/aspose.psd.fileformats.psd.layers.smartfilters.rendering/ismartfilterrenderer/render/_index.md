---
title: "ISmartFilterRenderer.Render"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ISmartFilterRenderer मेथड। वर्तमान स्मार्ट फ़िल्टर को पिक्सेल डेटा पर रेंडर करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/
---
{{< psd/tize >}}
## ISmartFilterRenderer.Render method

वर्तमान स्मार्ट फ़िल्टर को पिक्सेल डेटा पर रेंडर करता है।

```csharp
public PixelsData Render(PixelsData pixelsData)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pixelsData | PixelsData | पिक्सेल डेटा। |

### रिटर्न वैल्यू

प्रोसेस किए गए पिक्सेल डेटा को रिटर्न करता है।

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

* class [PixelsData](../../../aspose.psd/pixelsdata/)
* interface [ISmartFilterRenderer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* assembly [Aspose.PSD](../../../)


