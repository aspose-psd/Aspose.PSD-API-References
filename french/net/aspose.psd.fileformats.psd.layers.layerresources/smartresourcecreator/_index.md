---
title: Class SmartResourceCreator
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SmartResourceCreator classe. Définit la classe SmartResourceCreator qui peut créer des ressources PlLd SoLd et SoLe. Est utilisé pour prendre en charge les calques dobjets intelligents dans les images Adobe Photoshop.
type: docs
weight: 3000
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---
## SmartResourceCreator class

Définit la classe SmartResourceCreator qui peut créer des ressources PlLd, SoLd et SoLe. Est utilisé pour prendre en charge les calques d'objets intelligents dans les images Adobe® Photoshop®.

```csharp
public class SmartResourceCreator
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SmartResourceCreator](smartresourcecreator/#constructor)() | Initialise une nouvelle instance du`SmartResourceCreator` classe. |
| [SmartResourceCreator](smartresourcecreator/#constructor_1)(PlacedResource) | Initialise une nouvelle instance du`SmartResourceCreator` class avec le modèle donné. |
| [SmartResourceCreator](smartresourcecreator/#constructor_2)(bool, bool) | Initialise une nouvelle instance du`SmartResourceCreator` classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GeneratePlacedResource](../../aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/generateplacedresource/)() | Génère la ressource placée. |
| [GenerateSmartEmbeddedResource](../../aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/generatesmartembeddedresource/)() | Génère la ressource d'objet intelligent intégrée. |
| [GenerateSmartExternalResource](../../aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/generatesmartexternalresource/)() | Génère la ressource d'objet intelligent externe. |

### Exemples

Le code suivant illustre la prise en charge des ressources SoLEResource, SmartObjectResource et PlacedResource.

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

void CheckSmartObjectResourceValues(object[] expectedValue, SmartObjectResource resource)
{
    AssertAreEqual(expectedValue[0], resource.IsCustom);
    AssertAreEqual(expectedValue[2], resource.PageNumber);
    AssertAreEqual(expectedValue[3], resource.TotalPages);
    AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
    AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
    AssertAreEqual(8, resource.TransformMatrix.Length);
    AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
    AssertAreEqual(expectedValue[7], resource.Value);
    AssertAreEqual(expectedValue[8], resource.Perspective);
    AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
    AssertAreEqual(expectedValue[10], resource.Top);
    AssertAreEqual(expectedValue[11], resource.Left);
    AssertAreEqual(expectedValue[12], resource.Bottom);
    AssertAreEqual(expectedValue[13], resource.Right);
    AssertAreEqual(expectedValue[14], resource.UOrder);
    AssertAreEqual(expectedValue[15], resource.VOrder);

    AssertAreEqual(expectedValue[16], resource.Crop);
    AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
    AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
    AssertAreEqual(expectedValue[19], resource.DurationNumerator);
    AssertAreEqual(expectedValue[20], resource.DurationDenominator);
    AssertAreEqual(expectedValue[21], resource.FrameCount);
    AssertAreEqual(expectedValue[22], resource.Width);
    AssertAreEqual(expectedValue[23], resource.Height);
    AssertAreEqual(expectedValue[24], resource.Resolution);
    AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
    AssertAreEqual(expectedValue[26], resource.Comp);
    AssertAreEqual(expectedValue[27], resource.CompId);
    AssertAreEqual(expectedValue[28], resource.OriginalCompId);
    AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
    AssertAreEqual(expectedValue[30], resource.NonAffineTransformMatrix);
    if (resource.IsCustom)
    {
        AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
        AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
    }
}

void SetNewSmartValues(SmartObjectResource resource, object[] newValues)
{
    // Nous ne modifions pas ces valeurs dans la ressource
    newValues[0] = resource.IsCustom;
    newValues[1] = resource.UniqueId.ToString();
    newValues[5] = resource.PlacedLayerType;
    newValues[14] = resource.UOrder;
    newValues[15] = resource.VOrder;
    newValues[28] = resource.OriginalCompId;

    // Ces valeurs doivent également être modifiées dans PlLdResource (avec l'UniqueId spécifié)
    // et certains d'entre eux doivent être en accord avec l'objet intelligent de soulignement dans le LinkDataSource
    resource.PageNumber = (int)newValues[2]; // 2 ;
    resource.TotalPages = (int)newValues[3]; // 3 ;
    resource.AntiAliasPolicy = (int)newValues[4]; // 0 ;
    resource.TransformMatrix = (double[])newValues[6];
    resource.Value = (double)newValues[7]; // 1.23456789 ;
    resource.Perspective = (double)newValues[8]; // 0,123456789 ;
    resource.PerspectiveOther = (double)newValues[9]; // 0,987654321 ;
    resource.Top = (double)newValues[10]; // -126 ;
    resource.Left = (double)newValues[11]; // -215 ;
    resource.Bottom = (double)newValues[12]; // 248 ;
    resource.Right = (double)newValues[13]; // 145 ;
    resource.Crop = (int)newValues[16]; // 5 ;
    resource.FrameStepNumerator = (int)newValues[17]; // 1;
    resource.FrameStepDenominator = (int)newValues[18]; // 601 ;
    resource.DurationNumerator = (int)newValues[19]; // 2 ;
    resource.DurationDenominator = (int)newValues[20]; // 602 ;
    resource.FrameCount = (int)newValues[21]; // 11 ;
    resource.Width = (double)newValues[22]; // 541 ;
    resource.Height = (double)newValues[23]; // 249 ;
    resource.Resolution = (double)newValues[24]; // 144 ;
    resource.ResolutionUnit = (UnitTypes)newValues[25];
    resource.Comp = (int)newValues[26]; // 21 ;
    resource.CompId = (int)newValues[27]; // 22 ;
    resource.NonAffineTransformMatrix = (double[])newValues[30];

    // Cet identifiant unique doit être modifié dans les références s'il y en a
    resource.PlacedId = new Guid((string)newValues[29]);  // "12345678-9abc-def0-9876-54321fecba98");
    if (resource.IsCustom)
    {
        resource.HorizontalMeshPointUnit = (UnitTypes)newValues[31];
        resource.HorizontalMeshPoints = (double[])newValues[32];
        resource.VerticalMeshPointUnit = (UnitTypes)newValues[33];
        resource.VerticalMeshPoints = (double[])newValues[34];
    }

    // Attention à certains paramètres : l'image enregistrée peut devenir illisible par Adobe® Photoshop®
    ////ressource.UOrder = 6;
    ////ressource.VOrder = 9;

    // Ne changez rien sinon vous ne pourrez pas utiliser la transformation libre
    // ou changez l'objet intelligent de soulignement en type vectoriel
    ////resource.PlacedLayerType = PlacedLayerType.Vector ;

    // Il devrait y avoir une PlLdResource valide avec cet identifiant unique
    ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");
}

object[] newSmartValues = new object[]
{
    true,
    null,
    2,
    3,
    0,
    PlacedLayerType.ImageStack,
    new double[8]
    {
        12.937922786050663,
        19.419959734187131,
        2.85445817782261,
        1.0540625423957124,
        7.20861031651307,
        14.634102808208553,
        17.292074924741144,
        4
    },
    1.23456789,
    0.123456789,
    0.987654321,
    -126d,
    -215d,
    248d,
    145d,
    4,
    4,
    5,
    1,
    601,
    2,
    602,
    11,
    541d,
    249d,
    144d,
    UnitTypes.Percent,
    21,
    22,
    23,
    "12345678-9abc-def0-9876-54321fecba98",
    new double[8]
    {
        129.937922786050663,
        195.419959734187131,
        26.85445817782261,
        12.0540625423957124,
        72.20861031651307,
        147.634102808208553,
        175.292074924741144,
        42
    },
    UnitTypes.Points,
    new double[16]
    {
        0.01d, 103.33333333333433d, 206.66686666666666d, 310.02d,
        0.20d, 103.33333333333533d, 206.69666666666666d, 310.03d,
        30.06d, 103.33333333336333d, 206.66660666666666d, 310.04d,
        04.05d, 103.33333333373333d, 206.66666166666666d, 310.05d
    },
    UnitTypes.Distance,
    new double[16]
    {
        0.06d, 0.07d, 0.08d, 0.09d,
        49.066666666666664d, 49.266666666666664d, 49.566666666666664d, 49.766666666666664d,
        99.133333333333329d, 99.433333333333329d, 99.633333333333329d, 99.833333333333329d,
        140, 141, 142, 143,
    },
};

object[] expectedValues = new object[]
{
    new object[]
    {
        false,
        "5867318f-3174-9f41-abca-22f56a75247e",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
        0d,
        0d,
        0d,
        0d,
        0d,
        2d,
        2d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        2d,
        2d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "64b3997c-06e0-be40-a349-41acf397c897",
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
    }
};

var sourceFilePath = "rgb8_2x2_linked.psd";
var outputPath = "rgb8_2x2_linked_output.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLeResource soleResource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as SoLeResource;
            if (resource != null)
            {
                soleResource = resource;
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                CheckSmartObjectResourceValues(expectedValue, resource);
                SetNewSmartValues(resource, newSmartValues);

                break;
            }
        }
    }

    AssertIsTrue(soleResource != null);
    image.Save(outputPath, new PsdOptions(image));
    using (PsdImage savedImage = (PsdImage)Image.Load(outputPath))
    {
        foreach (Layer imageLayer in savedImage.Layers)
        {
            foreach (var imageResource in imageLayer.Resources)
            {
                var resource = imageResource as SoLeResource;
                if (resource != null)
                {
                    CheckSmartObjectResourceValues(newSmartValues, resource);

                    break;
                }
            }
        }
    }
}
```

### Voir également

* class [PlLdResource](../plldresource/)
* class [SoLdResource](../soldresource/)
* class [SoLeResource](../soleresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


