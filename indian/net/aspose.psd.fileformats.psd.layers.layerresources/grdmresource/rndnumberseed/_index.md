---
title: "GrdmResource.RndNumberSeed"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GrdmResource प्रॉपर्टी। नॉइज़ ग्रेडिएंट के लिए रंग उत्पन्न करने हेतु उपयोग किया जाने वाला रैंडम नंबर सीड"
type: docs
weight: 150
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/
---
{{< psd/tize >}}
## GrdmResource.RndNumberSeed property

Noise ग्रेडिएंट के लिए रंग उत्पन्न करने हेतु उपयोग किया गया रैंडम नंबर सीड।

```csharp
public int RndNumberSeed { get; set; }
```

## उदाहरण

निम्नलिखित कोड GrdmResource संसाधन के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // वर्तमान मानों की जाँच करें
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // दूसरे ग्रेडिएंट रंग बिंदु के लिए लाल रंग
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // बदलाव वाले मानों की जाँच करें
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### देखें भी

* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


