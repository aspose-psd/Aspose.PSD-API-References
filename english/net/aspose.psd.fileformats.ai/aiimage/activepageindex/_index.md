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

## Examples

The following code demonstrates support of ability to change active page in Ai images.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Load the AI image.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // By default, the ActivePageIndex is 0.
    // So if you save the AI image without changing this property, the first page will be rendered and saved.
    image.Save(firstPageOutputPng, new PngOptions());

    // Change the active page index to the second page.
    image.ActivePageIndex = 1;

    // Save the second page of the AI image as a PNG image.
    image.Save(secondPageOutputPng, new PngOptions());

    // Change the active page index to the third page.
    image.ActivePageIndex = 2;

    // Save the third page of the AI image as a PNG image.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### See Also

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


