---
title: "Classe SoLeResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLeResource class. Définit la classe SoLeResource qui contient des informations sur un calque d'objet dynamique dans un fichier PSD. Elle est utilisée pour prendre en charge les calques d'objets dynamiques avec des liens de fichiers externes dans les images Adobe Photoshop."
type: docs
weight: 3380
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/
---
{{< psd/tize >}}
## SoLeResource class

Définit la classe SoLeResource qui contient des informations sur un calque d’objet intelligent dans un fichier PSD. Elle est utilisée pour prendre en charge les calques d’objets intelligents avec des liens de fichiers externes dans les images Adobe® Photoshop®.

```csharp
public class SoLeResource : SmartObjectResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SoLeResource](soleresource/#constructor)() | Initialise une nouvelle instance de la classe `SoLeResource`. |
| [SoLeResource](soleresource/#constructor_1)(Guid, bool, bool) | Initialise une nouvelle instance de la classe `SoLeResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | Obtient ou définit la politique d'anticrénelage des données du calque d'objet dynamique dans l'image PSD. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | Obtient ou définit la position inférieure du calque placé dans l'image PSD. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | Obtient ou définit les limites du calque placé dans le fichier PSD. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | Obtient ou définit la valeur de comp des données du calque d'objet dynamique dans le fichier PSD. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | Obtient ou définit l'ID du comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. Les comps sont des compositions d'une mise en page que les concepteurs peuvent créer. En utilisant les comps de calque, vous pouvez créer, gérer et visualiser plusieurs versions d'une mise en page dans un seul fichier Adobe Photoshop. Un comp de calque est un instantané d'un état du panneau Calques. Les comps de calque enregistrent trois types d'options de calque mais cette propriété obtient l'identifiant de sélection du comp de calque pour le calque d'objet dynamique dans le fichier PSD. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | Obtient ou définit le recadrage des données du calque d'objet dynamique dans l'image PSD. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | Obtient ou définit le dénominateur de la durée. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | Obtient ou définit le numérateur de la durée. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | Obtient ou définit le nombre d'images des données du calque d'objet dynamique dans le fichier PSD. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | Obtient ou définit le dénominateur du pas d'image. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | Obtient ou définit le numérateur du pas d'image. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | Obtient ou définit la hauteur. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | Obtient ou définit l'unité de mesure des points de maillage horizontaux. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | Obtient ou définit une valeur indiquant si le style de déformation de cette instance est personnalisé. Si vrai, il contient des points de maillage. Si défini sur faux, il supprime les points de maillage. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | Obtient ou définit les éléments du descripteur des données du calque d'objet dynamique dans le fichier PSD. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | Obtient ou définit la position gauche du calque placé dans le fichier PSD. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | Obtient la longueur de la ressource d'objet dynamique en octets. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | Obtient ou définit la matrice de transformation non affine des données du calque d'objet dynamique dans le fichier PSD. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. Cette propriété obtient l'identifiant de sélection du Comp de calque original pour le calque d'objet dynamique dans le fichier PSD. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | Obtient ou définit le numéro de page des données du calque d'objet dynamique dans le fichier PSD. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | Obtient ou définit l'identifiant unique de ces données de calque d'objet dynamique dans l'image PSD. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | Obtient ou définit le type des données du calque d'objet dynamique dans le fichier PSD. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | Obtient ou définit la résolution des données du calque d'objet dynamique dans le fichier PSD. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | Obtient ou définit l'unité de mesure de la résolution des données du calque d'objet dynamique dans le fichier PSD. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | Obtient ou définit la position droite du calque placé dans le fichier PSD. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | Obtient ou définit la position supérieure du calque placé dans l'image PSD. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | Obtient ou définit le nombre total de pages des données du calque d'objet dynamique dans le fichier PSD. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | Obtient ou définit la matrice de transformation des données du calque d'objet dynamique dans le fichier PSD. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | Obtient ou définit l'identifiant unique global des données du calque d'objet dynamique [`SmartObjectResource`](../smartobjectresource/) dans l'image PSD. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | Obtient ou définit la valeur de déformation du calque placé dans l'image PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | Obtient la version du calque placé dans le fichier PSD, généralement 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | Obtient ou définit l'unité de mesure des points du maillage vertical. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | Obtient ou définit la valeur d'ordre V du calque placé dans le fichier PSD. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | Obtient ou définit la largeur. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | Enregistre la ressource d'objet dynamique dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soleresource/typetoolkey/) | Clé d'information de l'outil de texte : 'SoLE'. |

## Exemples

Le code suivant montre la prise en charge des ressources SoLEResource, SmartObjectResource et PlacedResource.

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
    // Ces valeurs nous ne les modifions pas dans la ressource.
    newValues[0] = resource.IsCustom;
    newValues[1] = resource.UniqueId.ToString();
    newValues[5] = resource.PlacedLayerType;
    newValues[14] = resource.UOrder;
    newValues[15] = resource.VOrder;
    newValues[28] = resource.OriginalCompId;

    // Ces valeurs doivent également être modifiées dans la PlLdResource (avec l'UniqueId spécifié).
    // et certaines d'entre elles doivent être en accord avec l'objet intelligent sous-jacent dans le LinkDataSource.
    resource.PageNumber = (int)newValues[2]; // 2;
    resource.TotalPages = (int)newValues[3]; // 3;
    resource.AntiAliasPolicy = (int)newValues[4]; // 0;
    resource.TransformMatrix = (double[])newValues[6];
    resource.Value = (double)newValues[7]; // 1.23456789;
    resource.Perspective = (double)newValues[8]; // 0.123456789;
    resource.PerspectiveOther = (double)newValues[9]; // 0.987654321;
    resource.Top = (double)newValues[10]; // -126;
    resource.Left = (double)newValues[11]; // -215;
    resource.Bottom = (double)newValues[12]; // 248;
    resource.Right = (double)newValues[13]; // 145;
    resource.Crop = (int)newValues[16]; // 5;
    resource.FrameStepNumerator = (int)newValues[17]; // 1;
    resource.FrameStepDenominator = (int)newValues[18]; // 601;
    resource.DurationNumerator = (int)newValues[19]; // 2;
    resource.DurationDenominator = (int)newValues[20]; // 602;
    resource.FrameCount = (int)newValues[21]; // 11;
    resource.Width = (double)newValues[22]; // 541;
    resource.Height = (double)newValues[23]; // 249;
    resource.Resolution = (double)newValues[24]; // 144;
    resource.ResolutionUnit = (UnitTypes)newValues[25];
    resource.Comp = (int)newValues[26]; // 21;
    resource.CompId = (int)newValues[27]; // 22;
    resource.NonAffineTransformMatrix = (double[])newValues[30];

    // Cet identifiant unique doit être modifié dans les références, le cas échéant.
    resource.PlacedId = new Guid((string)newValues[29]);  // "12345678-9abc-def0-9876-54321fecba98");
    if (resource.IsCustom)
    {
        resource.HorizontalMeshPointUnit = (UnitTypes)newValues[31];
        resource.HorizontalMeshPoints = (double[])newValues[32];
        resource.VerticalMeshPointUnit = (UnitTypes)newValues[33];
        resource.VerticalMeshPoints = (double[])newValues[34];
    }

    // Soyez prudent avec certains paramètres : l'image enregistrée peut devenir illisible par Adobe® Photoshop®.
    ////resource.UOrder = 6;
    ////resource.VOrder = 9;

    // Ne modifiez pas cela sinon vous ne pourrez pas utiliser la transformation libre.
    // ou changez l'objet intelligent sous-jacent en type vecteur.
    ////resource.PlacedLayerType = PlacedLayerType.Vector;

    // Il doit exister une PlLdResource valide avec cet identifiant unique.
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

### Voir aussi

* class [SmartObjectResource](../smartobjectresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


