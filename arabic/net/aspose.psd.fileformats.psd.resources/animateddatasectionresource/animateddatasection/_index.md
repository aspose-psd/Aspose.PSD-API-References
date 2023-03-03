---
title: AnimatedDataSectionResource.AnimatedDataSection
second_title: Aspose.PSD لمرجع .NET API
description: AnimatedDataSectionResource ملكية. الحصول على أو تعيين هيكل قسم البيانات المتحركة.
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/
---
## AnimatedDataSectionResource.AnimatedDataSection property

الحصول على أو تعيين هيكل قسم البيانات المتحركة.

```csharp
public AnimatedDataSectionStructure AnimatedDataSection { get; }
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

* class [AnimatedDataSectionStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/)
* class [AnimatedDataSectionResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../animateddatasectionresource/)
* المجسم [Aspose.PSD](../../../)


