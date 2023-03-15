---
title: Enum PsdVersion
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.PsdVersion एनुम. फ़इल स्वरूप संस्करण
type: docs
weight: 3600
url: /hi/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

फ़ाइल स्वरूप संस्करण

```csharp
public enum PsdVersion : byte
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Psd | `1` | डिफ़ॉल्ट PSD संस्करण. |
| Psb | `2` | PSB संस्करण. |

### उदाहरण

निम्न उदाहरण PSD फ़ाइल को PSB और इसके विपरीत में कनवर्ट करने की क्षमता दिखाता है।

```csharp
[C#]

string sourceFilePathPsb = "2layers.psb";
string outputFilePathPsd = "ConvertFromPsb.psd";
using (Image img = Image.Load(sourceFilePathPsb))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psd };
    img.Save(outputFilePathPsd, options);
}

string sourceFilePathPsd = "2layers.psd";
string outputFilePathPsb = "ConvertFromPsd.psb";
using (Image img = Image.Load(sourceFilePathPsd))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psb };
    img.Save(outputFilePathPsb, options);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* सभा [Aspose.PSD](../../)


