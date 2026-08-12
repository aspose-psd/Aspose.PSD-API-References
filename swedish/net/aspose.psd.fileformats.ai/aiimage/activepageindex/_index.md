---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD för .NET API‑referens"
description: "AiImage-egenskapen. Hämtar eller anger index för den aktiva sidan"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Hämtar eller anger index för den aktiva sidan.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Denna egenskap är endast aktuell för AI-bilden i PDF-format. Om bilden inte är i PDF-format eller det inte finns några sidor, kommer egenskapen att vara -1. Denna egenskap visar vilken sida av AI-bilden som kommer att användas som bas för rendering.

## Exempel

Följande kod demonstrerar stöd för möjligheten att ändra aktiv sida i Ai-bilder.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Läs in AI-bilden.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Som standard är ActivePageIndex 0.
    // Så om du sparar AI-bilden utan att ändra denna egenskap, kommer den första sidan att renderas och sparas.
    image.Save(firstPageOutputPng, new PngOptions());

    // Ändra index för aktiv sida till den andra sidan.
    image.ActivePageIndex = 1;

    // Spara den andra sidan av AI-bilden som en PNG-bild.
    image.Save(secondPageOutputPng, new PngOptions());

    // Ändra det aktiva sidindexet till den tredje sidan.
    image.ActivePageIndex = 2;

    // Spara den tredje sidan av AI-bilden som en PNG-bild.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Se även

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


