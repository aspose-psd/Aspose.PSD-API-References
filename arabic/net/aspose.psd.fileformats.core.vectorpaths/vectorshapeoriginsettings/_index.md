---
title: Class VectorShapeOriginSettings
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings فصل. إعدادات إنشاء شكل المتجه.
type: docs
weight: 1440
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

إعدادات إنشاء شكل المتجه.

```csharp
public sealed class VectorShapeOriginSettings
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | يقوم بتهيئة مثيل جديد لملف`VectorShapeOriginSettings` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على خاصية أركان مربع الأصل. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | الحصول على قيمة تشير إلى ما إذا كان هذا المثيل له خاصية فهرس الأصل. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل له خاصية مستطيل أصل نصف القطر. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل له خاصية دقة الأصل. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل له خاصية المستطيل. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | الحصول على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على خاصية نوع الأصل. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان الشكل غير صالح. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | الحصول على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على مجموعة خصائص غير صالحة للشكل. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على خاصية التحويل. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | الحصول على أو تعيين زوايا مربع الأصل. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | الحصول على فهرس شكل الأصل أو تعيينه. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | الحصول على أو تعيين مستطيل نصف قطر الأصل. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | الحصول على الدقة الأصلية أو تعيينها . |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | الحصول على المربع المحيط بالشكل الأصلي أو تعيينه. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | الحصول على نوع الأصل أو تحديده. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | الحصول على مصفوفة التحويل أو تعيينها. |

### أمثلة

يوضح المثال التالي دعم مورد VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // قراءة
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // التحرير
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* المجسم [Aspose.PSD](../../)


