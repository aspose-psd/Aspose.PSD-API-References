---
title: Class VectorShapeOriginSettings
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings τάξη. Ρυθμίσεις προέλευσης διανυσματικού σχήματος.
type: docs
weight: 1440
url: /el/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

Ρυθμίσεις προέλευσης διανυσματικού σχήματος.

```csharp
public sealed class VectorShapeOriginSettings
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`VectorShapeOriginSettings` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα γωνίες πλαισίου προέλευσης. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει ιδιότητα ευρετηρίου προέλευσης. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα ορθογώνιο ακτίνας προέλευσης. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει ιδιότητα ανάλυσης προέλευσης. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα ορθογώνιο. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει ιδιότητα τύπου προέλευσης. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι άκυρο. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το στιγμιότυπο έχει ένα σύνολο ιδιοτήτων ακυρωμένου σχήματος. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα μετασχηματισμού. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | Λαμβάνει ή ορίζει τις γωνίες του πλαισίου προέλευσης. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | Λαμβάνει ή ορίζει το ευρετήριο σχήματος προέλευσης. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | Λαμβάνει ή ορίζει το ορθογώνιο ακτίνας αρχής. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | Λαμβάνει ή ορίζει την αρχική ανάλυση. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | Λαμβάνει ή ορίζει το πλαίσιο οριοθέτησης του σχήματος προέλευσης. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο της προέλευσης. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη του πόρου VogkResource.

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

    // ΑΝΑΓΝΩΣΗ
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Επεξεργασία
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* συνέλευση [Aspose.PSD](../../)


