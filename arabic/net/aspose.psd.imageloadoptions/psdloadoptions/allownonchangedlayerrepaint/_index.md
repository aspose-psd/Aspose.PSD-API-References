---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdLoadOptions. يحصل أو يعيّن ما إذا كان يجب الحفاظ على بكسلات الطبقة الأصلية أثناء التصيير إذا لم يتم تعديل الطبقة"
type: docs
weight: 20
url: /ar/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

يحصل أو يعيّن ما إذا كان يجب الحفاظ على بكسلات الطبقة الأصلية أثناء العرض إذا لم يتم تعديل الطبقة.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` للحفاظ على بكسلات الطبقات غير المتغيّرة؛ وإلا `false`.

## أمثلة

الكود التالي يوضح السلوك الجديد الذي يمنع إعادة رسم الطبقات تلقائيًا قبل التغييرات.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### انظر أيضًا

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


