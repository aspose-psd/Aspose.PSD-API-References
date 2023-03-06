---
title: AnimatedDataSectionResource.AnimatedDataSection
second_title: Aspose.PSD for .NET API Referansı
description: AnimatedDataSectionResource mülk. Animasyonlu veri bölümü yapısını alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/
---
## AnimatedDataSectionResource.AnimatedDataSection property

Animasyonlu veri bölümü yapısını alır veya ayarlar.

```csharp
public AnimatedDataSectionStructure AnimatedDataSection { get; }
```

### Örnekler

Aşağıdaki kod, animasyonlu verilerin zaman çizelgesi çerçevesindeki gecikme süresinin nasıl ayarlanacağını/güncelleneceğini gösterir.

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

            // 1 saniyeye eşit olan 100 centi-saniye değerinde çerçeve gecikme kaydını oluşturur.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // zamanı santi saniye olarak ayarla.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Ayrıca bakınız

* class [AnimatedDataSectionStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/)
* class [AnimatedDataSectionResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../animateddatasectionresource/)
* toplantı [Aspose.PSD](../../../)


