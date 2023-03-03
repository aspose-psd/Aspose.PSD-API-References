---
title: AnimatedDataSectionStructure.Items
second_title: Aspose.PSD لمرجع .NET API
description: AnimatedDataSectionStructure ملكية. الحصول على أو تعيين هياكل قسم البيانات المتحركة.
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/
---
## AnimatedDataSectionStructure.Items property

الحصول على أو تعيين هياكل قسم البيانات المتحركة.

```csharp
public OSTypeStructure[] Items { get; }
```

### أمثلة

يوضح الكود التالي كيفية تعيين / تحديث وقت التأخير في إطار المخطط الزمني للبيانات المتحركة.

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

            // ينشئ سجل تأخير الإطار بقيمة 100 سنتي ثانية تساوي 1 ثانية.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // ضبط الوقت في سنتي ثانية.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### أنظر أيضا

* class [OSTypeStructure](../../ostypestructure/)
* class [AnimatedDataSectionStructure](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../animateddatasectionstructure/)
* المجسم [Aspose.PSD](../../../)


