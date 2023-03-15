---
title: Class AnimatedDataSectionResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.AnimatedDataSectionResource فصل. مورد البرنامج الإضافي لقسم البيانات المتحركة.
type: docs
weight: 3630
url: /ar/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---
## AnimatedDataSectionResource class

مورد البرنامج الإضافي لقسم البيانات المتحركة.

```csharp
public class AnimatedDataSectionResource : ResourceBlock
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AnimatedDataSection](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/) { get; } | الحصول على أو تعيين هيكل قسم البيانات المتحركة. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/datasize/) { get; } | الحصول على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | الحصول على أو تحديد المعرف الفريد للمورد. |
| [KeyName](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/keyname/) { get; } | اسم مفتاح المورد . |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/minimalversion/) { get; } | يحصل على الحد الأدنى من إصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | الحصول على اسم المورد أو تعيينه. سلسلة باسكال ، مبطن لجعل الحجم زوجياً (يتكون الاسم الفارغ من وحدتي بايت من 0) . |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا "8BIM" . |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | الحصول على حجم كتلة المورد بالبايت بما في ذلك البيانات الخاصة به. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد في الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد . |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* المجسم [Aspose.PSD](../../)


