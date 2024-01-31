---
title: AiImage.ActivePageIndex
second_title: Aspose.PSD for .NET API Reference
description: AiImage property. Gets or sets the index of the active page
type: docs
weight: 20
url: /net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Gets or sets the index of the active page.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

This property is only actual for PDF format AI image. If the image is not in PDF format or there are no pages, the property will be -1. This property shows which page of AI image will be the base for rendering.

### Exceptions

| exception | condition |
| --- | --- |
| IndexOutOfRangeException | There is no page in this document with index " + value.ToString() |

### See Also

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


