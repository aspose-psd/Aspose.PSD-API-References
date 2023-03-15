---
title: PsdImage.GlobalAngle
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage संपत्त. वैश्वक कण प्रप्त य सेट करत है
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

वैश्विक कोण प्राप्त या सेट करता है।

```csharp
public int GlobalAngle { get; set; }
```

### उदाहरण

निम्न कोड वैश्विक कोण मान को बदलने के लिए PsdImage.GlobalAngle गुण के लिए समर्थन प्रदर्शित करता है।

```csharp
[C#]

// जब DropShadowEffect.UseGlobalLight गुण 'true' है, तो DropShadowEffect ऑब्जेक्ट PsdImage.GlobalAngle गुण से कोण मान का उपयोग करता है।

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### यह सभी देखें

* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


