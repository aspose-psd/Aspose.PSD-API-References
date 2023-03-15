---
title: ObjectArrayStructure.ObjectArrayStructure
second_title: Aspose.PSD untuk Referensi .NET API
description: ObjectArrayStructure konstruktor. Menginisialisasi instance baru dariObjectArrayStructure kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/objectarraystructure/
---
## ObjectArrayStructure(string, string, OSTypeStructure[]) {#constructor_1}

Menginisialisasi instance baru dari[`ObjectArrayStructure`](../) kelas.

```csharp
public ObjectArrayStructure(string keyName, string classIdName, OSTypeStructure[] structures)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| keyName | String | Nama kunci. |
| classIdName | String | Nama pengenal kelas. |
| structures | OSTypeStructure[] | Struktur. |

### Contoh

Kode berikut menunjukkan dukungan tanda tangan ObAr dan UnFl.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### Lihat juga

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [ObjectArrayStructure](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure/)
* perakitan [Aspose.PSD](../../../)

---

## ObjectArrayStructure(int, ClassID, ClassID, string, OSTypeStructure[]) {#constructor}

Menginisialisasi instance baru dari[`ObjectArrayStructure`](../) kelas.

```csharp
public ObjectArrayStructure(int key, ClassID keyName, ClassID classID, string className, 
    OSTypeStructure[] structures)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| key | Int32 | Kunci bilangan bulat. |
| keyName | ClassID | Nama kunci. |
| classID | ClassID | Pengidentifikasi kelas. |
| className | String | Nama kelas. |
| structures | OSTypeStructure[] | Struktur. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | classID adalah nol |

### Contoh

Kode berikut menunjukkan dukungan tanda tangan ObAr dan UnFl.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### Lihat juga

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [ObjectArrayStructure](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure/)
* perakitan [Aspose.PSD](../../../)


