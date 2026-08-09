---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية AiImage. تحصل على أو تعيين فهرس الصفحة النشطة"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

يحصل أو يعيّن فهرس الصفحة النشطة.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

هذه الخاصية صالحة فقط لصورة AI بتنسيق PDF. إذا لم تكن الصورة بتنسيق PDF أو لا توجد صفحات، ستكون قيمة الخاصية -1. تُظهر هذه الخاصية أي صفحة من صورة AI ستكون الأساس للتصيير.

## أمثلة

الكود التالي يوضح دعم القدرة على تغيير الصفحة النشطة في صور Ai.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// حمّل صورة AI.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // بشكل افتراضي، يكون ActivePageIndex هو 0.
    // لذلك إذا قمت بحفظ صورة AI دون تغيير هذه الخاصية، سيتم تصيير الصفحة الأولى وحفظها.
    image.Save(firstPageOutputPng, new PngOptions());

    // غيّر فهرس الصفحة النشطة إلى الصفحة الثانية.
    image.ActivePageIndex = 1;

    // احفظ الصفحة الثانية من صورة AI كصورة PNG.
    image.Save(secondPageOutputPng, new PngOptions());

    // غيّر فهرس الصفحة النشطة إلى الصفحة الثالثة.
    image.ActivePageIndex = 2;

    // احفظ الصفحة الثالثة من صورة AI كصورة PNG.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### انظر أيضًا

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


