---
title: "Klasse VectorShapeOriginSettings"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings Klasse. Einstellungen für den Ursprung einer Vektorform."
type: docs
weight: 1450
url: /de/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

Einstellungen zur Ursprungserstellung von Vektorformen.

```csharp
public sealed class VectorShapeOriginSettings
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | Initialisiert eine neue Instanz der `VectorShapeOriginSettings`-Klasse. |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | Initialisiert eine neue Instanz der `VectorShapeOriginSettings`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Eigenschaft für die Ursprungskasten-Ecken hat. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Eigenschaft für den Ursprung-Index hat. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Eigenschaft für das Ursprung-Radius-Rechteck hat. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Eigenschaft für die Ursprung-Auflösung hat. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Rechteck-Eigenschaft hat. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Eigenschaft für den Ursprungstyp hat. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob die Form ungültig ist. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Eigenschaft für eine ungültige Form gesetzt hat. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Liest einen Wert, der angibt, ob diese Instanz die Transformations‑Eigenschaft hat. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | Liest oder legt die Ursprungskasten-Ecken fest. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | Liest oder legt den Ursprung-Form‑Index fest. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | Liest oder legt das Ursprung‑Radius‑Rechteck fest. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | Liest oder legt die Ursprung‑Auflösung fest. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | Liest oder setzt den Begrenzungsrahmen der Ursprungsgestalt. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | Liest oder setzt den Typ des Ursprungs. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | Liest oder setzt die Transformationsmatrix. |

## Beispiele

Das folgende Beispiel demonstriert die Unterstützung der VogkResource‑Ressource.

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

    // Lesen
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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


