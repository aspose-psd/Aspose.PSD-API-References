---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ResourceBlock फ़ील्ड. ImageReady का संसाधन हस्ताक्षर"
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady की रिसोर्स सिग्नेचर।

```csharp
public const int ResouceBlockMeSaSignature;
```

## उदाहरण

अगला कोड उदाहरण MeSa हस्ताक्षर वाले संसाधनों के साथ PSD फ़ाइलों को सही ढंग से लोड और सहेजने की क्षमता दर्शाता है।

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(2)1..psd";
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### देखें भी

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


