---
title: Class BorderInformationResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource klas. De bron met randinformatie van afdrukinstellingen voor afbeeldingen.
type: docs
weight: 3650
url: /nl/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
## BorderInformationResource class

De bron met randinformatie van afdrukinstellingen voor afbeeldingen.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Haalt de gegevensgrootte van de bron op in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Haalt de unieke identificatie voor de resource op of stelt deze in. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Krijgt de minimaal vereiste PSD-versie. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Haalt de resourcenaam op of stelt deze in. Pascal-tekenreeks, opgevuld om de grootte gelijk te maken (een null-naam bestaat uit twee bytes van 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Haalt de bronhandtekening op. Moet altijd '8BIM' zijn. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Haalt de grootte van het bronblok op in bytes inclusief de gegevens. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Haalt of stelt de grenseenheden in. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Haalt of stelt de randbreedte in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Slaat het bronblok op in de opgegeven stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valideert de bronwaarden. |

### Voorbeelden

Het volgende voorbeeld demonstreert de ondersteuning van de BorderInformationResource-resource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // update BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Zie ook

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* montage [Aspose.PSD](../../)


