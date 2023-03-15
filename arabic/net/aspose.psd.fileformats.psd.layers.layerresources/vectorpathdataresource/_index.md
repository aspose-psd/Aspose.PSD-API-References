---
title: Class VectorPathDataResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource فصل. Class VectorPathDataResource. يحتوي هذا المورد على معلومات حول قناع طبقة المتجه
type: docs
weight: 3340
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
## VectorPathDataResource class

Class VectorPathDataResource. يحتوي هذا المورد على معلومات حول قناع طبقة المتجه

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معطلاً. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معكوسًا. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | الحصول على أو تعيين سجلات المسار . |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | يحصل على نسخة مديرية الأمن العام . |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | يحصل على التوقيع. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | الحصول على الإصدار أو تحديده. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

### أمثلة

يوضح المثال التالي دعم معالجة Layer Vector Masks. كيف يتم تحرير المسارات وكيف يرسم Aspose.PSD الصورة النهائية.

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// قراءة
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // قم بإجراء تغييرات على نقاط مسار المتجه
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // تصدير
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


