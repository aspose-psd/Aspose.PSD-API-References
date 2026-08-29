---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "AiImage-Eigenschaft. Ruft den Index der aktiven Seite ab oder legt ihn fest"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Liest oder setzt den Index der aktiven Seite.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Diese Eigenschaft ist nur für AI-Bilder im PDF-Format gültig. Wenn das Bild nicht im PDF-Format vorliegt oder keine Seiten vorhanden sind, ist der Wert der Eigenschaft -1. Diese Eigenschaft zeigt, welche Seite des AI-Bildes als Basis für das Rendern verwendet wird.

## Beispiele

Der folgende Code demonstriert die Unterstützung der Möglichkeit, die aktive Seite in Ai-Bildern zu ändern.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Laden Sie das AI-Bild.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Standardmäßig ist der ActivePageIndex 0.
    // Wenn Sie also das AI-Bild speichern, ohne diese Eigenschaft zu ändern, wird die erste Seite gerendert und gespeichert.
    image.Save(firstPageOutputPng, new PngOptions());

    // Ändern Sie den Index der aktiven Seite auf die zweite Seite.
    image.ActivePageIndex = 1;

    // Speichern Sie die zweite Seite des AI-Bildes als PNG-Bild.
    image.Save(secondPageOutputPng, new PngOptions());

    // Ändern Sie den Index der aktiven Seite auf die dritte Seite.
    image.ActivePageIndex = 2;

    // Speichern Sie die dritte Seite des AI-Bildes als PNG-Bild.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Siehe auch

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


