---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ImageExtensions मेथड। Image को Image में परिवर्तित करता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Image को Image में परिवर्तित करता है।

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | परिवर्तित करने के लिए छवि। |

### रिटर्न वैल्यू

परिवर्तित छवि।

## टिप्पणियाँ

चेतावनी, GDI छवि *image* की तुलना में कम सीमाएँ प्राप्त कर सकती है। छवि के सभी भाग प्राप्त करने के लिए अधिक सुरक्षित एक्सटेंशन मेथड ToGdiImageFull का उपयोग करें।

### देखें भी

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


