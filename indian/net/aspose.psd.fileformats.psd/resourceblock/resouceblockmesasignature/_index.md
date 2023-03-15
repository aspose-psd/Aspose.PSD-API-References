---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ResourceBlock मैदन. ImageReady. क संसधन हस्तक्षर
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady. का संसाधन हस्ताक्षर

```csharp
public const int ResouceBlockMeSaSignature;
```

### उदाहरण

अगला कोड उदाहरण MeSa हस्ताक्षर वाले संसाधनों के साथ PSD फ़ाइलों को लोड करने और सहेजने की क्षमता प्रदर्शित करता है।

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(21..psd");
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### यह सभी देखें

* class [ResourceBlock](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* सभा [Aspose.PSD](../../../)


