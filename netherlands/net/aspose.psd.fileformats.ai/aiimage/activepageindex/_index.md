---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "AiImage-eigenschap. Haalt of stelt de index van de actieve pagina"
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Haalt of stelt de index van de actieve pagina.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Deze eigenschap is alleen van toepassing op AI-afbeeldingen in PDF-formaat. Als de afbeelding niet in PDF-formaat is of er geen pagina's zijn, zal de eigenschap -1 zijn. Deze eigenschap geeft aan welke pagina van de AI-afbeelding de basis zal vormen voor weergave.

## Voorbeelden

De volgende code demonstreert de mogelijkheid om de actieve pagina in AI-afbeeldingen te wijzigen.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Laad de AI-afbeelding.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Standaard is de ActivePageIndex 0.
    // Dus als je de AI-afbeelding opslaat zonder deze eigenschap te wijzigen, wordt de eerste pagina gerenderd en opgeslagen.
    image.Save(firstPageOutputPng, new PngOptions());

    // Wijzig de index van de actieve pagina naar de tweede pagina.
    image.ActivePageIndex = 1;

    // Sla de tweede pagina van de AI-afbeelding op als een PNG-afbeelding.
    image.Save(secondPageOutputPng, new PngOptions());

    // Wijzig de index van de actieve pagina naar de derde pagina.
    image.ActivePageIndex = 2;

    // Sla de derde pagina van de AI-afbeelding op als een PNG-afbeelding.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Zie ook

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


