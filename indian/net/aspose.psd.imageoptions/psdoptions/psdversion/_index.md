---
title: PsdOptions.PsdVersion
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdOptions संपत्त. फ़इल स्वरूप संस्करण प्रप्त य सेट करत है यह PSD य PSB. ह सकत है
type: docs
weight: 60
url: /hi/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

फ़ाइल स्वरूप संस्करण प्राप्त या सेट करता है। यह PSD या PSB. हो सकता है

```csharp
public PsdVersion PsdVersion { get; set; }
```

### संपत्ति मूल्य

फ़ाइल स्वरूप संस्करण.

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* नाम स्थान [Aspose.PSD.ImageOptions](../../psdoptions/)
* सभा [Aspose.PSD](../../../)


