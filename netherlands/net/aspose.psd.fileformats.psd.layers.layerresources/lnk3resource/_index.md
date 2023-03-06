---
title: Class Lnk3Resource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk3Resource klas. Definieert de klasse die informatie bevat over een ingebed bestand in het PSDformaat 32 bit per kanaalbeeld. De linkbron kan meerdereLiFdDataSource instanties die toegankelijk zijn voor indexer.
type: docs
weight: 2730
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---
## Lnk3Resource class

Definieert de klasse die informatie bevat over een ingebed bestand in het PSD-formaat 32 bit per kanaalbeeld. De linkbron kan meerdere[`LiFdDataSource`](../lifddatasource/) instanties die toegankelijk zijn voor indexer.

```csharp
public class Lnk3Resource : Lnk2Resource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Lnk3Resource](lnk3resource/)() | Initialiseert een nieuw exemplaar van het`Lnk3Resource` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Haalt het aantal linkgegevensbronnen op waartoe de indexer toegang heeft. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Krijgt een waarde die aangeeft of deze linkresource-instantie leeg is. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Krijgt de[`LiFdDataSource`](../lifddatasource/) op de opgegeven index. (2 indexers) |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Haalt de lengte van de PSD global link resource in bytes op. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Haalt de versie in PSD-formaat op. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Haalt de PSD global link resource signature op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Slaat de bronblokgegevens op. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

### Voorbeelden

Dit voorbeeld laat zien hoe u eigenschappen van de Lnk2Resource en Lnk3Resource kunt ophalen en instellen.

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

object[] Lnk2ResourceSupportCases = new object[]
{
new object[]
{
    "00af34a0-a90b-674d-a821-73ee508c5479",
    "rgb8_2x2.png",
    "png",
    string.Empty,
    0x53,
    0d,
    string.Empty,
    7,
    true,
    0x124L,
    0x74cL
}
};

object[] LayeredLnk2ResourceSupportCases = new object[]
{
new object[]
{
    "69ac1c0d-1b74-fd49-9c7e-34a7aa6299ef",
    "huset.jpg",
    "JPEG",
    string.Empty,
    0x9d46,
    0d,
    "xmp.did:0F94B342065B11E395B1FD506DED6B07",
    7,
    true,
    0x9E60L,
    0xc60cL
},
new object[]
{
    "5a7d1965-0eae-b24e-a82f-98c7646424c2",
    "panama-papers.jpg",
    "JPEG",
    string.Empty,
    0xF56B,
    0d,
    "xmp.did:BDE940CBF51B11E59D759CDA690663E3",
    7,
    true,
    0xF694L,
    0x10dd4L
},
};

object[] LayeredLnk3ResourceSupportCases = new object[]
{
new object[]
{
    "2fd7ba52-0221-de4c-bdc4-1210580c6caa",
    "panama-papers.jpg",
    "JPEG",
    string.Empty,
    0xF56B,
    0d,
    "xmp.did:BDE940CBF51B11E59D759CDA690663E3",
    7,
    true,
    0xF694l,
    0x10dd4L
},
new object[]
{
    "372d52eb-5825-8743-81a7-b6f32d51323d",
    "huset.jpg",
    "JPEG",
    string.Empty,
    0x9d46,
    0d,
    "xmp.did:0F94B342065B11E395B1FD506DED6B07",
    7,
    true,
    0x9E60L,
    0xc60cL
},
};

var basePath = "" + Path.DirectorySeparatorChar;
string Output = "output" + Path.DirectorySeparatorChar;

// Slaat de gegevens van een slim object in een PSD-bestand op in een bestand.
void SaveSmartObjectData(string prefix, string fileName, byte[] data)
{
    var filePath = basePath + prefix + "_" + fileName;

    using (var container = FileStreamContainer.CreateFileStream(filePath, false))
    {
        container.Write(data);
    }
}

// Laadt de nieuwe gegevens voor een slim object in een PSD-bestand.
byte[] LoadNewData(string fileName)
{
    using (var container = FileStreamContainer.OpenFileStream(basePath + fileName))
    {
        return container.ToBytes();
    }
}

// Krijgt en stelt eigenschappen in van de PSD Lnk2 / Lnk3 Resource en zijn liFD-gegevensbronnen in PSD-afbeelding
void ExampleOfLnk2ResourceSupport(
    string fileName,
    int dataSourceCount,
    int length,
    int newLength,
    object[] dataSourceExpectedValues)
{
    using (PsdImage image = (PsdImage)Image.Load(basePath + fileName))
    {
        Lnk2Resource lnk2Resource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnk2Resource = resource as Lnk2Resource;
            if (lnk2Resource != null)
            {
                AssertAreEqual(lnk2Resource.DataSourceCount, dataSourceCount);
                AssertAreEqual(lnk2Resource.Length, length);
                AssertAreEqual(lnk2Resource.IsEmpty, false);

                for (int i = 0; i < lnk2Resource.DataSourceCount; i++)
                {
                    LiFdDataSource lifdSource = lnk2Resource[i];
                    object[] expected = (object[])dataSourceExpectedValues[i];
                    AssertAreEqual(LinkDataSourceType.liFD, lifdSource.Type);
                    AssertAreEqual(new Guid((string)expected[0]), lifdSource.UniqueId);
                    AssertAreEqual(expected[1], lifdSource.OriginalFileName);
                    AssertAreEqual(expected[2], lifdSource.FileType.TrimEnd(' '));
                    AssertAreEqual(expected[3], lifdSource.FileCreator.TrimEnd(' '));
                    AssertAreEqual(expected[4], lifdSource.Data.Length);
                    AssertAreEqual(expected[5], lifdSource.AssetModTime);
                    AssertAreEqual(expected[6], lifdSource.ChildDocId);
                    AssertAreEqual(expected[7], lifdSource.Version);
                    AssertAreEqual((bool)expected[8], lifdSource.HasFileOpenDescriptor);
                    AssertAreEqual(expected[9], lifdSource.Length);

                    if (lifdSource.HasFileOpenDescriptor)
                    {
                        AssertAreEqual(-1, lifdSource.CompId);
                        AssertAreEqual(-1, lifdSource.OriginalCompId);
                        lifdSource.CompId = int.MaxValue;
                    }

                    SaveSmartObjectData(
                        Output + fileName,
                        lifdSource.OriginalFileName,
                        lifdSource.Data);
                    lifdSource.Data = LoadNewData("new_" + lifdSource.OriginalFileName);
                    AssertAreEqual(expected[10], lifdSource.Length);

                    lifdSource.ChildDocId = Guid.NewGuid().ToString();
                    lifdSource.AssetModTime = double.MaxValue;
                    lifdSource.FileType = "test";
                    lifdSource.FileCreator = "me";
                }

                AssertAreEqual(newLength, lnk2Resource.Length);
                break;
            }
        }

        AssertAreEqual(true, lnk2Resource != null);
        if (image.BitsPerChannel < 32) // 32 bit per kanaal opslaan wordt nog niet ondersteund
        {
            image.Save(basePath + Output + fileName, new PsdOptions(image));
        }
    }
}

// Dit voorbeeld laat zien hoe u eigenschappen van de PSD Lnk2 Resource en zijn liFD-gegevensbronnen voor 8 bit per kanaal kunt ophalen en instellen.
ExampleOfLnk2ResourceSupport("rgb8_2x2_embedded_png.psd", 1, 0x12C, 0x0000079c, Lnk2ResourceSupportCases);

// Dit voorbeeld laat zien hoe u eigenschappen van de PSD Lnk3-bron en de bijbehorende liFD-gegevensbronnen kunt ophalen en instellen voor 32 bit per kanaal.
ExampleOfLnk2ResourceSupport("Layered PSD file smart objects.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk3ResourceSupportCases);

// Dit voorbeeld laat zien hoe u eigenschappen van de PSD Lnk2 Resource en zijn liFD-gegevensbronnen voor 16 bit per kanaal kunt ophalen en instellen.
ExampleOfLnk2ResourceSupport("LayeredSmartObjects16bit.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk2ResourceSupportCases);
```

### Zie ook

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* class [Lnk2Resource](../lnk2resource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)

