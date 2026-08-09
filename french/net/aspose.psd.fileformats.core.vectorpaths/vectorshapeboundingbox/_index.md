---
title: "Classe VectorShapeBoundingBox"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeBoundingBox. Définit la classe de boîte englobante de forme vectorielle."
type: docs
weight: 1440
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/
---
{{< psd/tize >}}
## VectorShapeBoundingBox class

Définit la classe de boîte englobante de forme vectorielle.

```csharp
public sealed class VectorShapeBoundingBox
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VectorShapeBoundingBox](vectorshapeboundingbox/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/bottom/) { get; set; } | Obtient ou définit le bas. |
| [Bounds](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/bounds/) { get; set; } | Obtient ou définit les limites de la boîte englobante de la forme. |
| [Left](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/left/) { get; set; } | Obtient ou définit la gauche. |
| [PointsUnitType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/pointsunittype/) { get; set; } | Obtient ou définit le type d'unité des points qui déterminent les coins de la boîte. |
| [QuadVersion](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/quadversion/) { get; set; } | Obtient ou définit la version quad de la valeur d'unité. |
| [Right](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/right/) { get; set; } | Obtient ou définit la droite. |
| [Top](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/top/) { get; set; } | Obtient ou définit le haut. |

## Exemples

Cet exemple montre que le chargement et l'enregistrement de l'image PSD avec des calques de forme et des chemins vectoriels fonctionnent correctement.

```csharp
[C#]

// Cet exemple montre que le chargement et l'enregistrement de l'image PSD avec des calques de forme et des chemins vectoriels fonctionnent correctement.
string sourcePath = "vectorShapes.psd";
string outputFilePath = "output_vectorShapes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourcePath))
{
    var resource = GetVogkResource(image);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(0, setting.OriginIndex);
    var originalSetting = resource.ShapeOriginSettings[0];
    originalSetting.IsShapeInvalidated = true;
    resource.ShapeOriginSettings = new[]
    {
        originalSetting,
        new VectorShapeOriginSettings()
        {
            OriginIndex = 1,
            OriginResolution = 144,
            OriginType = 4,
            OriginShapeBox = new VectorShapeBoundingBox()
            {
                Bounds = Rectangle.FromLeftTopRightBottom(10, 15, 40, 70)
            }
        },
        new VectorShapeOriginSettings()
        {
            OriginIndex = 2,
            OriginResolution = 301,
            OriginType = 5,
            OriginRadiiRectangle = new VectorShapeRadiiRectangle()
            {
                TopLeft = 2,
                TopRight = 6,
                BottomLeft = 23,
                BottomRight = 42,
                QuadVersion = 1
            }
        }
    };

    image.Save(outputFilePath, new PsdOptions());
}

using (PsdImage image = (PsdImage)Image.Load(outputFilePath))
{
    var resource = GetVogkResource(image);
    AssertAreEqual(3, resource.ShapeOriginSettings.Length);

    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(true, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsShapeInvalidated);

    setting = resource.ShapeOriginSettings[1];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(1, setting.OriginIndex);
    AssertAreEqual(144.0, setting.OriginResolution);
    AssertAreEqual(4, setting.OriginType);
    AssertAreEqual(Rectangle.FromLeftTopRightBottom(10, 15, 40, 70), setting.OriginShapeBox.Bounds);

    setting = resource.ShapeOriginSettings[2];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(false, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(true, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(2, setting.OriginIndex);
    AssertAreEqual(301.0, setting.OriginResolution);
    AssertAreEqual(5, setting.OriginType);
    AssertAreEqual(2.0, setting.OriginRadiiRectangle.TopLeft);
    AssertAreEqual(6.0, setting.OriginRadiiRectangle.TopRight);
    AssertAreEqual(23.0, setting.OriginRadiiRectangle.BottomLeft);
    AssertAreEqual(42.0, setting.OriginRadiiRectangle.BottomRight);
    AssertAreEqual(1, setting.OriginRadiiRectangle.QuadVersion);
}

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
        throw new Exception("VogkResource not found.");
    }

    return resource;
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}
```

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


