---
title: VectorShapeOriginSettings
second_title: Aspose.PSD für .NET-API-Referenz
description: VektorformUrsprungseinstellungen.
type: docs
weight: 1440
url: /de/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

Vektorform-Ursprungseinstellungen.

```csharp
public sealed class VectorShapeOriginSettings
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings#constructor)() | Initialisiert eine neue Instanz von[`VectorShapeOriginSettings`](../vectorshapeoriginsettings) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz die Eigenschaft Ecken des Ursprungsfelds hat. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz über die Ursprungsindexeigenschaft verfügt. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz die Eigenschaft Ursprungsradienrechteck hat. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz über die Ursprungsauflösungseigenschaft verfügt. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz die Rechteckeigenschaft hat. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz über die Ursprungstyp-Eigenschaft verfügt. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Form ungültig ist. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz einen für ungültig erklärten Eigenschaftssatz hat. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz die Transformationseigenschaft hat. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners) { get; set; } | Ruft die Ecken der Ursprungsbox ab oder legt sie fest. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex) { get; set; } | Ruft den Ursprungsformindex ab oder legt ihn fest. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle) { get; set; } | Ruft das Ursprungsradius-Rechteck ab oder legt es fest. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution) { get; set; } | Ruft die Ursprungsauflösung ab oder legt sie fest. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox) { get; set; } | Ruft den Begrenzungsrahmen der Ursprungsform ab oder legt ihn fest. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype) { get; set; } | Ruft den Ursprungstyp ab oder legt ihn fest. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform) { get; set; } | Ruft die Transformationsmatrix ab oder setzt sie. |

### Beispiele

Das folgende Beispiel demonstriert die Unterstützung der VogkResource-Ressource.

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

    // Lektüre
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Bearbeiten
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
