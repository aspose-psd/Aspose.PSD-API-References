---
title: "एनम ColorSpace"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace एनम। रंग स्पेस प्रकार"
type: docs
weight: 4160
url: /hi/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

कलर स्पेस प्रकार।

```csharp
public enum ColorSpace : ushort
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| RGB | `0` | RGB रंग स्पेस। |
| HSB | `1` | HSB रंग स्पेस। |
| CMYK | `2` | CMYK रंग स्पेस। |
| Lab | `7` | Lab रंग स्पेस। |
| GrayScale | `8` | ग्रे स्केल रंग स्पेस। |

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

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


