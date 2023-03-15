---
title: Class Lnk3Resource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk3Resource clase. Define la clase que contiene información sobre un archivo incrustado en formato PSD de 32 bits por imagen de canal. El recurso de enlace puede contener variosLiFdDataSource instancias a las que puede acceder indexer.
type: docs
weight: 2730
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---
## Lnk3Resource class

Define la clase que contiene información sobre un archivo incrustado en formato PSD de 32 bits por imagen de canal. El recurso de enlace puede contener varios[`LiFdDataSource`](../lifddatasource/) instancias a las que puede acceder indexer.

```csharp
public class Lnk3Resource : Lnk2Resource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Lnk3Resource](lnk3resource/)() | Inicializa una nueva instancia del`Lnk3Resource` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtiene el recuento de orígenes de datos de vínculos a los que puede acceder el indexador. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtiene un valor que indica si esta instancia de recurso de enlace está vacía. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Obtiene el[`LiFdDataSource`](../lifddatasource/) en el índice especificado. (2 indexers) |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/key/) { get; } | Obtiene la clave de recurso de la capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtiene la longitud del recurso de enlace global PSD en bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Obtiene la versión en formato PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Obtiene la firma del recurso de enlace global PSD. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Guarda los datos del bloque de recursos. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ejemplos

Este ejemplo demuestra cómo obtener y establecer propiedades de Lnk2Resource y Lnk3Resource.

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

// Guarda los datos de un objeto inteligente en un archivo PSD en un archivo.
void SaveSmartObjectData(string prefix, string fileName, byte[] data)
{
    var filePath = basePath + prefix + "_" + fileName;

    using (var container = FileStreamContainer.CreateFileStream(filePath, false))
    {
        container.Write(data);
    }
}

// Carga los datos nuevos para un objeto inteligente en un archivo PSD.
byte[] LoadNewData(string fileName)
{
    using (var container = FileStreamContainer.OpenFileStream(basePath + fileName))
    {
        return container.ToBytes();
    }
}

// Obtiene y establece las propiedades del recurso PSD Lnk2 / Lnk3 y sus fuentes de datos liFD en la imagen PSD
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
        if (image.BitsPerChannel < 32) // Aún no se admite el ahorro de 32 bits por canal
        {
            image.Save(basePath + Output + fileName, new PsdOptions(image));
        }
    }
}

// Este ejemplo demuestra cómo obtener y establecer las propiedades del recurso PSD Lnk2 y sus fuentes de datos liFD para 8 bits por canal.
ExampleOfLnk2ResourceSupport("rgb8_2x2_embedded_png.psd", 1, 0x12C, 0x0000079c, Lnk2ResourceSupportCases);

// Este ejemplo demuestra cómo obtener y establecer las propiedades del recurso PSD Lnk3 y sus fuentes de datos liFD para 32 bits por canal.
ExampleOfLnk2ResourceSupport("Layered PSD file smart objects.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk3ResourceSupportCases);

// Este ejemplo demuestra cómo obtener y establecer las propiedades del recurso PSD Lnk2 y sus fuentes de datos liFD para 16 bits por canal.
ExampleOfLnk2ResourceSupport("LayeredSmartObjects16bit.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk2ResourceSupportCases);
```

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* class [Lnk2Resource](../lnk2resource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


