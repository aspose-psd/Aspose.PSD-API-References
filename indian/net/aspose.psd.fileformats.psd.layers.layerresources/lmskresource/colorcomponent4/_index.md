---
title: "LmskResource.ColorComponent4"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LmskResource प्रॉपर्टी। रंग घटक 4 प्राप्त करता है"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/
---
{{< psd/tize >}}
## LmskResource.ColorComponent4 property

रंग घटक 4 को प्राप्त करता है।

```csharp
public ushort ColorComponent4 { get; set; }
```

### Property Value

रंग घटक 4।

## उदाहरण

निम्नलिखित कोड दर्शाता है कि 16-बिट इमेजेज पर लेयर मास्क डिस्प्ले विकल्पों को LmskResource प्रॉपर्टीज़ बदलकर कैसे बदलें।

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 16-बिट छवि लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource खोजें।
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource गुण जाँचें।
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource गुण बदलें।
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // छवि सहेजें।
    image.Save(outputPsd);
}
```

### देखें भी

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


