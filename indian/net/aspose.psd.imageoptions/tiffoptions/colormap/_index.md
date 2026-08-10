---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "TiffOptions प्रॉपर्टी। रंग मानचित्र को प्राप्त करता है या सेट करता है"
type: docs
weight: 70
url: /hi/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

रंग मानचित्र को प्राप्त या सेट करता है।

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

रंग मानचित्र।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | मान |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | रंग मानचित्र केवल तब परिभाषित किया जा सकता है जब पिक्सेल प्रति नमूना 1 के बराबर हो। या नमूना प्रति बिट परिभाषित नहीं हैं। |
| ArgumentOutOfRangeException | value;ऐरे की लंबाई निम्न सूत्र के अनुरूप होनी चाहिए: 3 * (2**BitsPerSample)। |

### देखें भी

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


