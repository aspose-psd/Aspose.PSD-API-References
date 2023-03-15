---
title: Class BackgroundColorResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource klass. Resursen med raminformation för bildutskriftsinställningar.
type: docs
weight: 3640
url: /sv/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
## BackgroundColorResource class

Resursen med raminformation för bildutskriftsinställningar.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | Hämtar eller ställer in bakgrundsfärgen. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | Hämtar resursdatastorleken i byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Hämtar eller ställer in den unika identifieraren för resursen. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | Får den minsta nödvändiga PSD-versionen. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Hämtar eller ställer in resursnamnet. Pascal-sträng, vadderad för att göra storleken jämn (ett nollnamn består av två byte på 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Hämtar resurssignaturen. Bör alltid vara '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Hämtar resursblockstorleken i byte inklusive dess data. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Sparar resursblocket till den angivna strömmen. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validerar resursvärdena. |

### Exempel

Följande exempel visar stödet för BackgroundColorResource-resursen.

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

    // uppdatera BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Se även

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* hopsättning [Aspose.PSD](../../)


