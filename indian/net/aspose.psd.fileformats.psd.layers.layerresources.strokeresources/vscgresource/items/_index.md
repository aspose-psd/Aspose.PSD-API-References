---
title: "VscgResource.Items"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VscgResource प्रॉपर्टी। संरचना आइटम्स की एरे को प्राप्त करता है या सेट करता है। चेतावनी: Items एरे के मानों को KeyForData प्रॉपर्टी से मेल खाना चाहिए जो Items के भीतर संरचनाओं में संग्रहीत फ़िल सेटिंग्स के प्रकार को निर्धारित करता है।"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/
---
{{< psd/tize >}}
## VscgResource.Items property

संरचना आइटम्स की एरे प्राप्त करता या सेट करता है। **Warning:** `Items` एरे मानों को `KeyForData` प्रॉपर्टी के साथ मेल खाना चाहिए, जो `Items` के भीतर संरचनाओं में संग्रहीत फ़िल सेटिंग्स के प्रकार को निर्धारित करता है।

```csharp
public OSTypeStructure[] Items { get; }
```

### Property Value

[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) आइटम्स की एरे।

## उदाहरण

निम्नलिखित कोड VscgResource के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// परिवर्तनों की जाँच कर रहा है
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### देखें भी

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [VscgResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


