---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "TiffStreamReader विधि। स्ट्रीम से साइन किए गए इंटीजर मानों की एक सरणी पढ़ता है"
type: docs
weight: 140
url: /hi/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

स्ट्रीम से साइन किए गए पूर्णांक मानों की एक सरणी पढ़ता है।

```csharp
public int[] ReadSLongArray(long position, long count)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्थिति | Int64 | पढ़ने के लिए स्थिति। |
| count | Int64 | तत्वों की गिनती। |

### रिटर्न वैल्यू

साइन किए गए इंटीजर मानों की सरणी।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | count;कुल बाइट्स गिनती नकारात्मक है। + count + x4= + totalBytes |

### देखें भी

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


