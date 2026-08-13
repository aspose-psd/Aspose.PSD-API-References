---
title: "Sınıf AnimatedDataSectionStructure"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure sınıfı. Animasyonlu veriye sahip bölüm."
type: docs
weight: 2510
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
{{< psd/tize >}}
## AnimatedDataSectionStructure class

Animasyonlu veri içeren bölüm.

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | Animasyonlu veri bölüm yapısını alır veya ayarlar. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | Yapı anahtarını alır. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Anahtar adını alır veya ayarlar. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | [`OSTypeStructure`](../ostypestructure/) uzunluğunu bayt olarak alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Başlık uzunluğunu alır. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | AnDs'nin yapı anahtarını tanımlar. |

## Örnekler

Aşağıdaki kod, animasyonlu verinin zaman çizelgesi çerçevesinde gecikme süresini ayarlama/güncelleme yöntemini gösterir.

```csharp
[C#]

string sourceFile = "3_animated.psd";
string outputPsd = "output_3_animated.psd";

T FindStructure<T>(IEnumerable<OSTypeStructure> structures, string keyName) where T : OSTypeStructure
{
    foreach (var structure in structures)
    {
        if (structure.KeyName.ClassName == keyName)
        {
            return structure as T;
        }
    }

    return null;
}

OSTypeStructure[] AddOrReplaceStructure(IEnumerable<OSTypeStructure> structures, OSTypeStructure newStructure)
{
    List<OSTypeStructure> listOfStructures = new List<OSTypeStructure>(structures);

    for (int i = 0; i < listOfStructures.Count; i++)
    {
        OSTypeStructure structure = listOfStructures[i];
        if (structure.KeyName.ClassName == newStructure.KeyName.ClassName)
        {
            listOfStructures.RemoveAt(i);
            break;
        }
    }

    listOfStructures.Add(newStructure);

    return listOfStructures.ToArray();
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var imageResource in image.ImageResources)
    {
        if (imageResource is AnimatedDataSectionResource)
        {
            var animatedData =
                (AnimatedDataSectionStructure) (imageResource as AnimatedDataSectionResource).AnimatedDataSection;
            var framesList = FindStructure<ListStructure>(animatedData.Items, "FrIn");

            var frame1 = (DescriptorStructure)framesList.Types[1];

            // 1 saniyeye eşit 100 santisaniye değerine sahip çerçeve gecikme kaydını oluşturur.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Ayrıca Bakınız

* class [OSTypeStructure](../ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


