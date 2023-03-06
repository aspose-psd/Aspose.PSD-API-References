---
title: Class VectorShapeOriginSettings
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings klas. Instellingen voor het ontstaan van vectorvormen.
type: docs
weight: 1440
url: /nl/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

Instellingen voor het ontstaan van vectorvormen.

```csharp
public sealed class VectorShapeOriginSettings
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | Initialiseert een nieuw exemplaar van het`VectorShapeOriginSettings` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie de eigenschap origin box corners heeft. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie de eigenschap origin index heeft. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie de rechthoekeigenschap origin radii heeft. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie de eigenschap origin resolution heeft. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie de eigenschap rectangle heeft. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie een eigenschap van het oorsprongstype heeft. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de vorm ongeldig is. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie een eigenschappenset heeft met ongeldige vorm. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Krijgt een waarde die aangeeft of deze instantie de eigenschap transform heeft. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | Haalt of stelt de hoeken van het oorspronkelijke vak in. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | Haalt of stelt de oorsprongsvormindex in. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | Haalt of stelt de rechthoek van oorsprongstralen in. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | Haalt of stelt de oorspronkelijke resolutie in. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | Hiermee wordt het begrenzingsvak van de oorspronkelijke vorm opgehaald of ingesteld. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | Haalt of stelt het type van de oorsprong in. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | Haalt de transformatiematrix op of stelt deze in. |

### Voorbeelden

Het volgende voorbeeld demonstreert de ondersteuning van VogkResource-resource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Lezing
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Bewerken
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* montage [Aspose.PSD](../../)


