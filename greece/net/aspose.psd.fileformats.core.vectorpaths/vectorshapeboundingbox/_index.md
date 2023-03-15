---
title: Class VectorShapeBoundingBox
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeBoundingBox τάξη. Ορίζει την κλάση πλαισίου οριοθέτησης διανυσματικού σχήματος.
type: docs
weight: 1430
url: /el/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/
---
## VectorShapeBoundingBox class

Ορίζει την κλάση πλαισίου οριοθέτησης διανυσματικού σχήματος.

```csharp
public sealed class VectorShapeBoundingBox
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [VectorShapeBoundingBox](vectorshapeboundingbox/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/bottom/) { get; set; } | Παίρνει ή θέτει το κάτω μέρος. |
| [Bounds](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/bounds/) { get; set; } | Λαμβάνει ή ορίζει τα όρια του πλαισίου οριοθέτησης σχήματος. |
| [Left](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/left/) { get; set; } | Παίρνει ή ορίζει το αριστερό. |
| [QuadVersion](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/quadversion/) { get; set; } | Λαμβάνει ή ορίζει την τετραπλή έκδοση της τιμής μονάδας. |
| [Right](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/right/) { get; set; } | Παίρνει ή ορίζει το σωστό. |
| [Top](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/top/) { get; set; } | Παίρνει ή θέτει την κορυφή. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει ότι η φόρτωση και η αποθήκευση της εικόνας PSD με επίπεδα σχήματος και διανυσματικές διαδρομές λειτουργεί σωστά.

```csharp
[C#]

// Αυτό το παράδειγμα δείχνει ότι η φόρτωση και η αποθήκευση της εικόνας PSD με επίπεδα σχήματος και διανυσματικές διαδρομές λειτουργεί σωστά.
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

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* συνέλευση [Aspose.PSD](../../)


