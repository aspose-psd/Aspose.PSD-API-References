---
title: "تعداد ReadOnlyMode"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.ImageLoadOptions.ReadOnlyMode. يحدد أوضاع القراءة فقط المتاحة عند تحميل صورة PSD"
type: docs
weight: 5260
url: /ar/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

يحدد أوضاع القراءة فقط المتاحة عند تحميل صورة PSD.

```csharp
public enum ReadOnlyMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لم تُطبق أي قيود قراءة فقط. يمكن تعديل الصورة بالكامل. |
| Default | `1` | الوضع الافتراضي. الصورة في وضع القراءة فقط بالكامل ولا يمكن تعديلها. |
| MetadataEdit | `2` | يسمح بتحرير بيانات تعريف الصورة مع الحفاظ على محتوى الصورة في وضع القراءة فقط. |

## أمثلة

يوضح تحرير وحفظ بيانات تعريف PSD باستخدام ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // تغيير بيانات التعريف في ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // حفظ بيانات التعريف المعدلة في ReadOnlyMode
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### انظر أيضًا

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


