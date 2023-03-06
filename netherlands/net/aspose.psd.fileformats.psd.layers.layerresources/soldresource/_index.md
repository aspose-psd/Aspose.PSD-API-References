---
title: Class SoLdResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLdResource klas. Definieert de SoLdResourceklasse die informatie bevat over een slimme objectlaag in een PSDbestand. Wordt gebruikt om slimme objectlagen te ondersteunen in de Adobe Photoshopafbeeldingen.
type: docs
weight: 3020
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
## SoLdResource class

Definieert de SoLdResource-klasse die informatie bevat over een slimme objectlaag in een PSD-bestand. Wordt gebruikt om slimme objectlagen te ondersteunen in de Adobe® Photoshop®-afbeeldingen.

```csharp
public class SoLdResource : SmartObjectResource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SoLdResource](soldresource/#constructor)() | Initialiseert een nieuw exemplaar van het`SoLdResource` class. Deze standaardconstructor is ontworpen voor gebruik doorSoLdResourceLoader . Gebruik[`SmartResourceCreator`](../smartresourcecreator/) voor het maken van SoLdResource-klassen. |
| [SoLdResource](soldresource/#constructor_1)(Guid, bool, bool) | Initialiseert een nieuw exemplaar van het`SoLdResource` class. Het is noodzakelijk om de eigenschap Items in te stellen of InitializeItems() aan te roepen om een kant-en-klare instantie te krijgen. Deze constructor is ontworpen voor gebruik door[`SmartResourceCreator`](../smartresourcecreator/) en in eenheidstests. Gebruik[`SmartResourceCreator`](../smartresourcecreator/) voor het maken van SoLdResource-klassen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | Hiermee wordt het anti-aliasbeleid van de slimme objectlaaggegevens in de PSD-afbeelding opgehaald of ingesteld. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | Haalt de onderste locatie van de geplaatste laag in de PSD-afbeelding op of stelt deze in. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | Haalt de comp-waarde van de slimme objectlaaggegevens in het PSD-bestand op of stelt deze in. [Laagcomposities in slimme objecten](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | Haalt of stelt de ID in van de momenteel geselecteerde comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd. Comps zijn composities van een paginalay-out die ontwerpers kunnen maken. Met laagsamenstellingen kunt u meerdere versies van een lay-out in één Adobe® Photoshop®-bestand maken, beheren en bekijken. Een laagsamenstelling is een momentopname van een toestand van het deelvenster Lagen. Laagcomposities slaan drie soorten laagopties op, maar deze eigenschap krijgt de Layer Comp-selectie-ID voor de slimme objectlaag in het PSD-bestand. [Laagcomposities in slimme objecten](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | Hiermee wordt de uitsnede van de gegevens van de slimme objectlaag in de PSD-afbeelding opgehaald of ingesteld. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | Haalt of stelt de duurnoemer in. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | Haalt of stelt de duurteller in. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | Hiermee wordt het aantal frames van de slimme objectlaaggegevens in het PSD-bestand opgehaald of ingesteld. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | Haalt de noemer van de framestap op of stelt deze in. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | Haalt de framestapteller op of stelt deze in. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | Haalt of stelt de hoogte in. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | Haalt of stelt de horizontale mesh-punten van de geplaatste laag in het PSD-bestand in. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | Hiermee wordt de maateenheid van de horizontale netpunten opgehaald of ingesteld. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of deze instantie warp-stijl aangepast is. Indien waar bevat deze mesh-punten. Indien ingesteld op false, worden mesh-punten gewist. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | Haalt of stelt de descriptoritems van de slimme objectlaaggegevens in het PSD-bestand op. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/key/) { get; } | Haalt de resourcesleutel SoLd slimme objectlaag op. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | Haalt of stelt de linkerlocatie van de geplaatste laag in het PSD-bestand in. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | Haalt de resourcelengte van het slimme object op in bytes. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | Haalt of stelt de niet-affiene transformatiematrix van de slimme objectlaaggegevens in het PSD-bestand op. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | Haalt de originele ID op van de momenteel geselecteerde Comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd. Deze eigenschap haalt de originele laag Comp-selectie-ID op voor de slimme objectlaag in het PSD-bestand. [Laagcomposities in slimme objecten](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | Haalt of stelt het paginanummer van de slimme objectlaaggegevens in het PSD-bestand in. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | Haalt de perspectiefwaarde van de geplaatste laag in het PSD-bestand op of stelt deze in. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | Haalt of stelt de unieke identificatie van deze slimme objectlaaggegevens in de PSD-afbeelding in. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | Haalt of stelt het type slimme objectlaaggegevens in het PSD-bestand in. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion/) { get; } | Haalt de minimale psd-versie op die vereist is voor de slimme objectresource. 0 geeft geen beperkingen aan. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | Haalt de resolutie op van de slimme objectlaaggegevens in het PSD-bestand of stelt deze in. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | Hiermee wordt de resolutiemaateenheid van de slimme objectlaaggegevens in het PSD-bestand opgehaald of ingesteld. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | Haalt of stelt de juiste locatie van de geplaatste laag in het PSD-bestand in. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature/) { get; } | Haalt de slimme objectbronhandtekening op. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | Haalt of stelt het totale aantal pagina's van de slimme objectlaaggegevens in het PSD-bestand op. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | Hiermee wordt de transformatiematrix van de slimme objectlaaggegevens in het PSD-bestand opgehaald of ingesteld. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | Haalt de globale unieke identificatie van de slimme objectlaaggegevens op of stelt deze in[`SmartObjectResource`](../smartobjectresource/) in de PSD-afbeelding. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | Haalt of stelt de U-volgordewaarde van de geplaatste laag in het PSD-bestand in. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | Haalt de warpwaarde van de geplaatste laag in de PSD-afbeelding op of stelt deze in. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | Haalt de versie op van de geplaatste laag in het PSD-bestand, meestal 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | Haalt of stelt de horizontale mesh-punten van de geplaatste laag in het PSD-bestand in. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | Hiermee wordt de maateenheid van de verticale netpunten opgehaald of ingesteld. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | Haalt de V-volgordewaarde van de geplaatste laag in het PSD-bestand op of stelt deze in. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | Haalt of stelt de breedte in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | Slaat de slimme objectbron op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey/) | De type tool info sleutel: 'SoLd'. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van de SoLdResource-resource.

```csharp
[C#]

// Dit voorbeeld laat zien hoe u de gegevenseigenschappen van de slimme objectlaag van het PSD-bestand kunt ophalen of instellen.

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

                // Deze waarden moeten ook worden gewijzigd in de PlLdResource (met de opgegeven UniqueId).
                // en sommige moeten in overeenstemming zijn met het onderstreepte slimme object in de LinkDataSource
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

                // Deze unieke ID moet in eventuele referenties worden gewijzigd
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // Wees voorzichtig met sommige parameters: de afbeelding kan onleesbaar worden door Adobe® Photoshop®
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // Wijzig dit niet, anders kunt u geen gratis transformatie gebruiken
                // of verander het onderstreepte slimme object in het vectortype
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // Er moet een geldige PlLdResource zijn met deze unieke ID
                ////resource.UniqueId = nieuwe GUID ("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### Zie ook

* class [SmartObjectResource](../smartobjectresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


