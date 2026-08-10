---
title: "Enum PsdVersion"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.PsdVersion enum. फ़ाइल फ़ॉर्मेट संस्करण"
type: docs
weight: 4060
url: /hi/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

फ़ाइल फ़ॉर्मेट संस्करण

```csharp
public enum PsdVersion : byte
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Psd | `1` | डिफ़ॉल्ट PSD संस्करण। |
| Psb | `2` | PSB संस्करण। |

## उदाहरण

निम्नलिखित उदाहरण दिखाता है कि PSD फ़ाइल को PSB में और इसके विपरीत कैसे परिवर्तित किया जा सकता है।

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

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


