---
title: "Classe SoLdResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLdResource classe. Définit la classe SoLdResource qui contient des informations sur un calque d'objet dynamique dans un fichier PSD. Est utilisée pour prendre en charge les calques d'objets dynamiques dans les images Adobe Photoshop."
type: docs
weight: 3370
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
{{< psd/tize >}}
## SoLdResource class

Définit la classe SoLdResource qui contient des informations sur un calque d’objet intelligent dans un fichier PSD. Elle est utilisée pour prendre en charge les calques d’objets intelligents dans les images Adobe® Photoshop®.

```csharp
public class SoLdResource : SmartObjectResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SoLdResource](soldresource/#constructor)() | Initialise une nouvelle instance de la classe `SoLdResource`. Ce constructeur par défaut est conçu pour être utilisé par SoLdResourceLoader. Utilisez [`SmartResourceCreator`](../smartresourcecreator/) pour créer des classes SoLdResource. |
| [SoLdResource](soldresource/#constructor_1)(Guid, bool, bool) | Initialise une nouvelle instance de la classe `SoLdResource`. Il est nécessaire de définir la propriété Items ou d'appeler InitializeItems() pour obtenir une instance prête. Ce constructeur est conçu pour être utilisé par [`SmartResourceCreator`](../smartresourcecreator/) et dans les tests unitaires. Utilisez [`SmartResourceCreator`](../smartresourcecreator/) pour créer des classes SoLdResource. |

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
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey/) | La clé d'information de l'outil type : 'SoLd'. |

## Exemples

Le code suivant démontre la prise en charge de la ressource SoLdResource.

```csharp
[C#]

// Cet exemple montre comment obtenir ou définir les propriétés des données du calque d'objet dynamique du fichier PSD.

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

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
var outputFilePath = "LayeredSmartObjects8bit2_output.psd";
var expectedValues = new object[]
{
    new object[]
    {
        true,
        "76f05a3b-7523-5e42-a1bb-27f4735bffa0",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        149d,
        310d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        310d,
        149d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "d3388655-19e4-9742-82f2-f553bb01046a",
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 0.0d, 0.0d, 0.0d,
            49.666666666666664d, 49.666666666666664d, 49.666666666666664d, 49.666666666666664d,
            99.333333333333329d, 99.333333333333329d, 99.333333333333329d, 99.333333333333329d,
            149, 149, 149, 149,
        },
    },
    new object[]
    {
        true,
        "cf0477a8-8f92-ac4f-9462-f78e26234851",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        721d,
        1280d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        1280d,
        721d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "625cc4b9-2c5f-344f-8636-03caf2bd3489",
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 0.0, 0.0, 0.0,
            240.33333333333331, 240.33333333333331, 240.33333333333331, 240.33333333333331,
            480.66666666666663, 480.66666666666663, 480.66666666666663, 480.66666666666663,
            721, 721, 721, 721,
        },
        0,
        0
    }
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLdResource resource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            resource = imageResource as SoLdResource;
            if (resource != null)
            {
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[0], resource.IsCustom);
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
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
                AssertAreEqual((IEnumerable)expectedValue[30], resource.NonAffineTransformMatrix);
                if (resource.IsCustom)
                {
                    AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
                    AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
                    var temp = resource.VerticalMeshPoints;
                    resource.VerticalMeshPoints = resource.HorizontalMeshPoints;
                    resource.HorizontalMeshPoints = temp;
                }

                // Ces valeurs doivent également être modifiées dans la PlLdResource (avec l'UniqueId spécifié).
                // et certaines d'entre elles doivent être en accord avec l'objet intelligent sous-jacent dans le LinkDataSource.
                resource.PageNumber = 2;
                resource.TotalPages = 3;
                resource.AntiAliasPolicy = 0;
                resource.Value = 1.23456789;
                resource.Perspective = 0.123456789;
                resource.PerspectiveOther = 0.987654321;
                resource.Top = -126;
                resource.Left = -215;
                resource.Bottom = 248;
                resource.Right = 145;
                resource.Crop = 4;
                resource.FrameStepNumerator = 1;
                resource.FrameStepDenominator = 601;
                resource.DurationNumerator = 2;
                resource.DurationDenominator = 602;
                resource.FrameCount = 11;
                resource.Width = 541;
                resource.Height = 249;
                resource.Resolution = 144;
                resource.Comp = 21;
                resource.CompId = 22;
                resource.TransformMatrix = new double[8]
                {
                    12.937922786050663,
                    19.419959734187131,
                    2.85445817782261,
                    1.0540625423957124,
                    7.20861031651307,
                    14.634102808208553,
                    17.292074924741144,
                    4
                };
                resource.NonAffineTransformMatrix = new double[8]
                {
                    129.937922786050663,
                    195.419959734187131,
                    26.85445817782261,
                    12.0540625423957124,
                    72.20861031651307,
                    147.634102808208553,
                    175.292074924741144,
                    42
                };

                // Cet identifiant unique doit être modifié dans les références, le cas échéant.
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // Soyez prudent avec certains paramètres : l'image peut devenir illisible par Adobe® Photoshop®.
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // Ne modifiez pas cela sinon vous ne pourrez pas utiliser la transformation libre.
                // ou changez l'objet intelligent sous-jacent en type vecteur.
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // Il doit exister une PlLdResource valide avec cet identifiant unique.
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### Voir aussi

* class [SmartObjectResource](../smartobjectresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


