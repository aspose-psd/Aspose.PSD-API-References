---
title: SoLdResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonSoLdResourceaspose.psd.fileformats.psd.layers.layerresources/soldresource class. Es ist notwendig die ItemsEigenschaft zu setzen oder InitializeItems aufzurufen um eine fertige Instanz zu erhalten. Dieser Konstruktor ist für die Verwendung von by konzipiertSmartResourceCreatoraspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator und in Einheitentests. VerwendenSmartResourceCreatoraspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator zum Erstellen von SoLdResourceKlassen.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/soldresource/
---
## SoLdResource(Guid, bool, bool) {#constructor_1}

Initialisiert eine neue Instanz von[`SoLdResource`](../../soldresource) class. Es ist notwendig, die Items-Eigenschaft zu setzen oder InitializeItems() aufzurufen, um eine fertige Instanz zu erhalten. Dieser Konstruktor ist für die Verwendung von by konzipiert[`SmartResourceCreator`](../../smartresourcecreator) und in Einheitentests. Verwenden[`SmartResourceCreator`](../../smartresourcecreator) zum Erstellen von SoLdResource-Klassen.

```csharp
public SoLdResource(Guid uniqueId, bool isCustom, bool hasCompInfo)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | Guid | Der eindeutige Bezeichner der Smart-Object-Layer-Daten[`SoLdResource`](../../soldresource). |
| isCustom | Boolean | wenn eingestellt`Stimmt` [ist Brauch]. |
| hasCompInfo | Boolean | wenn eingestellt`Stimmt` [hat Comp-Informationen]. |

### Beispiele

Der folgende Code demonstriert die Unterstützung der SoLdResource-Ressource.

```csharp
[C#]

// Dieses Beispiel zeigt, wie die Dateneigenschaften der Smart-Objektebene der PSD-Datei abgerufen oder festgelegt werden.

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

                // Diese Werte sollten auch in der PlLdResource (mit der angegebenen UniqueId) geändert werden
                // und einige von ihnen müssen mit dem unterstreichenden Smart-Objekt in der LinkDataSource übereinstimmen
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

                // Diese eindeutige ID sollte gegebenenfalls in Referenzen geändert werden
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // Seien Sie vorsichtig mit einigen Parametern: Das Bild kann von Adobe® Photoshop® unlesbar werden
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // Ändern Sie dies nicht, sonst können Sie die freie Transformation nicht verwenden
                // oder ändern Sie das unterstreichende Smart-Objekt in den Vektortyp
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // Es sollte eine gültige PlLdResource mit dieser eindeutigen ID geben
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### Siehe auch

* class [SoLdResource](../../soldresource)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../soldresource)
* Montage [Aspose.PSD](../../../)

---

## SoLdResource() {#constructor}

Initialisiert eine neue Instanz von[`SoLdResource`](../../soldresource) class. Dieser Standardkonstruktor ist für die Verwendung von by konzipiertSoLdResourceLoader . verwenden[`SmartResourceCreator`](../../smartresourcecreator) zum Erstellen von SoLdResource-Klassen.

```csharp
public SoLdResource()
```

### Siehe auch

* class [SoLdResource](../../soldresource)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../soldresource)
* Montage [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->