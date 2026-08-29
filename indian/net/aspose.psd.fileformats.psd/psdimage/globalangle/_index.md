---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage प्रॉपर्टी। ग्लोबल एंगल प्राप्त करता या सेट करता है"
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

ग्लोबल एंगल को प्राप्त करता है या सेट करता है।

```csharp
public int GlobalAngle { get; set; }
```

## उदाहरण

निम्नलिखित कोड PsdImage.GlobalAngle प्रॉपर्टी के समर्थन को दर्शाता है ताकि वैश्विक कोण मान बदला जा सके।

```csharp
[C#]

// जब DropShadowEffect.UseGlobalLight प्रॉपर्टी 'true' हो, तो DropShadowEffect ऑब्जेक्ट PsdImage.GlobalAngle प्रॉपर्टी से कोण मान का उपयोग करता है।

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### देखें भी

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


