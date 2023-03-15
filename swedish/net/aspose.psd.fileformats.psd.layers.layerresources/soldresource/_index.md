---
title: Class SoLdResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLdResource klass. Definierar klassen SoLdResource som innehåller information om ett smart objektlager i en PSDfil. Is används för att stödja smarta objektlager i Adobe Photoshopbilderna.
type: docs
weight: 3020
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
## SoLdResource class

Definierar klassen SoLdResource som innehåller information om ett smart objektlager i en PSD-fil. Is används för att stödja smarta objektlager i Adobe® Photoshop®-bilderna.

```csharp
public class SoLdResource : SmartObjectResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SoLdResource](soldresource/#constructor)() | Initierar en ny instans av`SoLdResource` class. Denna standardkonstruktor är designad för att använda avSoLdResourceLoader . Använd[`SmartResourceCreator`](../smartresourcecreator/) för att skapa SoLdResource-klasser. |
| [SoLdResource](soldresource/#constructor_1)(Guid, bool, bool) | Initierar en ny instans av`SoLdResource` class. Det är nödvändigt att ställa in Items-egenskapen eller anropa InitializeItems() för att få en klar instans. Denna konstruktor är designad för att använda av[`SmartResourceCreator`](../smartresourcecreator/) och i enhetstester. Använd[`SmartResourceCreator`](../smartresourcecreator/) för att skapa SoLdResource-klasser. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | Hämtar eller ställer in anti-alias-policyn för data för smarta objektlager i PSD-bilden. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | Hämtar eller ställer in den nedre platsen för det placerade lagret i PSD-bilden. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | Hämtar eller ställer in gränserna för det placerade lagret i PSD-filen. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | Hämtar eller ställer in kompvärdet för data för smarta objektlager i PSD-filen. [Layer comps i Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | Hämtar eller ställer in ID för den för närvarande valda komp för det underordnade dokumentet, vilket kommer att vara -1 om ingen är vald. Comps är sammansättningar av en sidlayout som designers kan skapa. Med hjälp av lagersammansättningar kan du skapa, hantera och visa flera versioner av en layout i en enda Adobe® Photoshop®-fil. En lagerkomp är en ögonblicksbild av ett tillstånd på panelen Lager. Layer Comps sparar tre typer av lageralternativ men den här egenskapen får Layer Comp-urvalsidentifieraren för det smarta objektlagret i PSD-filen. [Layer comps i Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | Hämtar eller ställer in beskärningen av data för smarta objektlager i PSD-bilden. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | Hämtar eller ställer in varaktighetsnämnaren. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | Hämtar eller ställer in varaktighetsräknaren. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | Hämtar eller ställer in bildruteantalet för smarta objektlagerdata i PSD-filen. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | Hämtar eller ställer in ramstegsnämnaren. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | Hämtar eller ställer in bildstegstäljaren. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | Hämtar eller ställer in höjden. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | Hämtar eller ställer in de horisontella mesh-punkterna för det placerade lagret i PSD-filen. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | Hämtar eller ställer in måttenheten för de horisontella maskpunkterna. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om denna instansförvrängningsstil är anpassad. Om den är sant innehåller den mesh-punkter. Om den är inställd på false raderas mesh-punkter. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | Hämtar eller ställer in deskriptorobjekten för data för smarta objektlager i PSD-filen. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/key/) { get; } | Hämtar resursnyckeln SoLd smarta objektlager. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | Hämtar eller ställer in den vänstra platsen för det placerade lagret i PSD-filen. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | Hämtar resurslängden för smarta objekt i byte. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | Hämtar eller ställer in den icke-affina transformationsmatrisen för data för smarta objektlager i PSD-filen. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för det underordnade dokumentet, vilket kommer att vara -1 om ingen är markerad. Den här egenskapen får den ursprungliga lager Comp-urvalsidentifieraren för det smarta objektlagret i PSD-filen. [Layer comps i Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | Hämtar eller ställer in sidnumret för data för smarta objektlager i PSD-filen. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | Hämtar eller ställer in perspektivvärdet för det placerade lagret i PSD-filen. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | Hämtar eller ställer in perspektivets andra värde för det placerade lagret i PSD-filen. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | Hämtar eller ställer in den unika identifieraren för denna smarta objektlagerdata i PSD-bilden. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | Hämtar eller ställer in typen av smart objektlagerdata i PSD-filen. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion/) { get; } | Får den minimala psd-version som krävs för resursen för smarta objekt. 0 indikerar inga begränsningar. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | Hämtar eller ställer in upplösningen för data för smarta objektlager i PSD-filen. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | Hämtar eller ställer in upplösningsmåttenheten för data för smarta objektlager i PSD-filen. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | Hämtar eller ställer in rätt plats för det placerade lagret i PSD-filen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature/) { get; } | Får resurssignaturen för smarta objekt. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | Hämtar eller ställer in den övre platsen för det placerade lagret i PSD-bilden. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | Hämtar eller ställer in det totala sidnumret för data för smarta objektlager i PSD-filen. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | Hämtar eller ställer in transformationsmatrisen för data för smarta objektlager i PSD-filen. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | Hämtar eller ställer in den globala unika identifieraren för data för smarta objektlager[`SmartObjectResource`](../smartobjectresource/) i PSD-bilden. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | Hämtar eller ställer in U-ordervärdet för det placerade lagret i PSD-filen. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | Hämtar eller ställer in varpvärdet för det placerade lagret i PSD-bilden. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | Hämtar versionen av det placerade lagret i PSD-filen, vanligtvis 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | Hämtar eller ställer in de horisontella mesh-punkterna för det placerade lagret i PSD-filen. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | Hämtar eller ställer in måttenheten för de vertikala maskpunkterna. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | Hämtar eller ställer in V-ordningens värde för det placerade lagret i PSD-filen. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | Hämtar eller ställer in bredden. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | Sparar den smarta objektresursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey/) | Typverktygets infonyckel: 'SoLd'. |

### Exempel

Följande kod visar stödet för SoLdResource-resursen.

```csharp
[C#]

// Det här exemplet visar hur man hämtar eller ställer in dataegenskaperna för smarta objektlager för PSD-filen.

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

                // Dessa värden bör också ändras i PlLdResource (med det angivna UniqueId).
                // och några av dem måste vara i överensstämmelse med det understrukna smarta objektet i LinkDataSource
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

                // Detta unika ID bör ändras i referenser om några
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // Var försiktig med vissa parametrar: bilden kan bli oläslig av Adobe® Photoshop®
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // Ändra inte detta annars kommer du inte att kunna använda gratis transform
                // eller ändra det understrykande smarta objektet till vektortypen
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // Det bör finnas en giltig PlLdResource med detta unika ID
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### Se även

* class [SmartObjectResource](../smartobjectresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


