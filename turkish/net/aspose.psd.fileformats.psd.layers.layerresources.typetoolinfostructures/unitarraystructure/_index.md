---
title: "Sınıf UnitArrayStructure"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.UnitArrayStructure sınıfı. Double değerler dizisini ve ölçü birimlerini tutan UnitArrayStructure sınıfını tanımlar. Genellikle ObjectArrayStructure tarafından PSD dosyası kaynaklarında kullanılır."
type: docs
weight: 3660
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---
{{< psd/tize >}}
## UnitArrayStructure class

Double değerler dizisini ve ölçü birimlerini tutan UnitArrayStructure sınıfını tanımlar. Genellikle PSD dosyası kaynaklarında, [`ObjectArrayStructure`](../objectarraystructure/) tarafından kullanılır.

```csharp
public sealed class UnitArrayStructure : OSTypeStructure
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [UnitArrayStructure](unitarraystructure/)(ClassID, UnitTypes, double[]) | Yeni bir `UnitArrayStructure` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/key/) { get; } | Bu birim dizi yapısı anahtarını alır. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Anahtar adını alır veya ayarlar. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/length/) { get; } | [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır. |
| [UnitType](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unittype/) { get; set; } | `UnitArrayStructure` değerlerinin ölçü birimi tipini alır veya ayarlar. |
| [ValueCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/valuecount/) { get; } | Değer sayısını alır. |
| [Values](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/) { get; set; } | Birim dizi yapısı değerlerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Başlık uzunluğunu alır. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/structurekey/) | 'UnFl' `UnitArrayStructure` anahtarını tanımlar. |

## Örnekler

Aşağıdaki kod, ObAr ve UnFl imzalarının desteğini gösterir.

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

### Ayrıca Bakınız

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


