---
title: "GrdmResource.Roughness"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GrdmResource प्रॉपर्टी। रफ़नेस फैक्टर। जब ग्रेडिएंट प्रकार नॉइज़ हो तो हम रफ़नेस 0 से 2048 तक असाइन कर सकते हैं"
type: docs
weight: 160
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/
---
{{< psd/tize >}}
## GrdmResource.Roughness property

रफ़नेस फ़ैक्टर। जब 'Gradient type' = 'Noise' हो, तो हम 'Roughness' (0 - 2048) असाइन कर सकते हैं।

```csharp
public int Roughness { get; set; }
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


