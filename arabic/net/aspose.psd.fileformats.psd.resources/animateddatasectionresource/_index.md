---
title: "الفئة AnimatedDataSectionResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Resources.AnimatedDataSectionResource. مورد ملحق قسم البيانات المتحركة."
type: docs
weight: 4090
url: /ar/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---
{{< psd/tize >}}
## AnimatedDataSectionResource class

مورد المكوّن الإضافي لقسم البيانات المتحركة.

```csharp
public class AnimatedDataSectionResource : ResourceBlock
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnimatedDataSection](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/) { get; } | يحصل أو يضبط بنية قسم البيانات المتحركة. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/datasize/) { get; } | يحصل على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | يحصل أو يضبط المعرف الفريد للمورد. |
| [KeyName](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/keyname/) { get; } | اسم مفتاح المورد. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/minimalversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | يحصل أو يضبط اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين من الصفر). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد إلى الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد. |

## أمثلة

الكود التالي يوضح كيفية تعيين/تحديث وقت التأخير في إطار المخطط الزمني للبيانات المتحركة.

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

            // ينشئ سجل تأخير الإطار بقيمة 100 سنتي-ثانية وهو ما يعادل 1 ثانية.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### انظر أيضًا

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


