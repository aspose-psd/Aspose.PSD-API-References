---
title: Class Lnk3Resource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk3Resource classe. Définit la classe qui contient des informations sur un fichier embarqué au format PSD 32 bits par canal image. La ressource lien peut contenir plusieursLiFdDataSource instances accessibles par indexer.
type: docs
weight: 2730
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---
## Lnk3Resource class

Définit la classe qui contient des informations sur un fichier embarqué au format PSD 32 bits par canal image. La ressource lien peut contenir plusieurs[`LiFdDataSource`](../lifddatasource/) instances accessibles par indexer.

```csharp
public class Lnk3Resource : Lnk2Resource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Lnk3Resource](lnk3resource/)() | Initialise une nouvelle instance du`Lnk3Resource` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtient le nombre de sources de données de liens accessibles par l'indexeur. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtient une valeur indiquant si cette instance de ressource de lien est vide. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Obtient le[`LiFdDataSource`](../lifddatasource/) à l'index spécifié. (2 indexers) |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtient la longueur de ressource de lien global PSD en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Obtient la version du format PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Obtient la signature de ressource de lien global PSD. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Enregistre les données du bloc de ressources. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Exemples

Cet exemple montre comment obtenir et définir les propriétés de Lnk2Resource et Lnk3Resource.

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

// Enregistre les données d'un objet intelligent dans un fichier PSD dans un fichier.
void SaveSmartObjectData(string prefix, string fileName, byte[] data)
{
    var filePath = basePath + prefix + "_" + fileName;

    using (var container = FileStreamContainer.CreateFileStream(filePath, false))
    {
        container.Write(data);
    }
}

// Charge les nouvelles données d'un objet intelligent dans le fichier PSD.
byte[] LoadNewData(string fileName)
{
    using (var container = FileStreamContainer.OpenFileStream(basePath + fileName))
    {
        return container.ToBytes();
    }
}

// Obtient et définit les propriétés de la ressource PSD Lnk2 / Lnk3 et de ses sources de données liFD dans l'image PSD
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
        if (image.BitsPerChannel < 32) // L'enregistrement 32 bits par canal n'est pas encore pris en charge
        {
            image.Save(basePath + Output + fileName, new PsdOptions(image));
        }
    }
}

// Cet exemple montre comment obtenir et définir les propriétés de la ressource PSD Lnk2 et de ses sources de données liFD pour 8 bits par canal.
ExampleOfLnk2ResourceSupport("rgb8_2x2_embedded_png.psd", 1, 0x12C, 0x0000079c, Lnk2ResourceSupportCases);

// Cet exemple montre comment obtenir et définir les propriétés de la ressource PSD Lnk3 et de ses sources de données liFD pour 32 bits par canal.
ExampleOfLnk2ResourceSupport("Layered PSD file smart objects.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk3ResourceSupportCases);

// Cet exemple montre comment obtenir et définir les propriétés de la ressource PSD Lnk2 et de ses sources de données liFD pour 16 bits par canal.
ExampleOfLnk2ResourceSupport("LayeredSmartObjects16bit.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk2ResourceSupportCases);
```

### Voir également

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* class [Lnk2Resource](../lnk2resource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


