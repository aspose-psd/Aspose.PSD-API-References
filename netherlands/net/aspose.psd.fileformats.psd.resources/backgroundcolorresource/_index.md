---
title: Class BackgroundColorResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource klas. De bron met randinformatie van afdrukinstellingen voor afbeeldingen.
type: docs
weight: 3640
url: /nl/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
## BackgroundColorResource class

De bron met randinformatie van afdrukinstellingen voor afbeeldingen.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | Krijgt of stelt de achtergrondkleur in. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | Haalt de gegevensgrootte van de bron op in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Haalt de unieke identificatie voor de resource op of stelt deze in. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | Krijgt de minimaal vereiste PSD-versie. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Haalt de resourcenaam op of stelt deze in. Pascal-tekenreeks, opgevuld om de grootte gelijk te maken (een null-naam bestaat uit twee bytes van 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Haalt de bronhandtekening op. Moet altijd '8BIM' zijn. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Haalt de grootte van het bronblok op in bytes inclusief de gegevens. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Slaat het bronblok op in de opgegeven stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valideert de bronwaarden. |

### Voorbeelden

In het volgende voorbeeld wordt de ondersteuning van de BackgroundColorResource-resource gedemonstreerd.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // update BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Zie ook

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* montage [Aspose.PSD](../../)


