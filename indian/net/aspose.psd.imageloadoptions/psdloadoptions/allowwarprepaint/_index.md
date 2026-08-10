---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdLoadOptions प्रॉपर्टी। यह निर्धारित करता है कि रेंडर की गई इमेज को वॉर्प ट्रांसफ़ॉर्म के साथ या बिना सहेजा जाए या नहीं।"
type: docs
weight: 30
url: /hi/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

रेंडर की गई इमेज के साथ, वॉर्प ट्रांसफ़ॉर्म के साथ या बिना, सहेजना चाहिए या नहीं, इसे प्राप्त करता है या सेट करता है।

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` वॉर्प ट्रांसफ़ॉर्मेशन के साथ इमेज रेंडर करें `false`।

## उदाहरण

निम्नलिखित कोड वॉर्प इफ़ेक्ट रेंडरिंग को दर्शाता है।

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### देखें भी

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


