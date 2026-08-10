---
title: "GrdmResource.GradientMode"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GrdmResource प्रॉपर्टी। इस ग्रेडिएंट का मोड ग्रेडिएंट प्रकार निर्धारित करता है  ठोस/शोर 0/1"
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/
---
{{< psd/tize >}}
## GrdmResource.GradientMode property

इस ग्रेडिएंट के लिए मोड निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)।

```csharp
public GradientKind GradientMode { get; set; }
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

* enum [GradientKind](../../../aspose.psd.fileformats.psd.layers.gradient/gradientkind/)
* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


