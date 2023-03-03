---
title: Class XmpPacketWrapper
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Xmp.XmpPacketWrapper فصل. يحتوي على حزمة xmp متسلسلة بما في ذلك الرأس والمقطورة.
type: docs
weight: 6290
url: /ar/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

يحتوي على حزمة xmp متسلسلة بما في ذلك الرأس والمقطورة.

```csharp
public class XmpPacketWrapper
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | يقوم بتهيئة مثيل جديد لملف`XmpPacketWrapper` فئة . |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | يقوم بتهيئة مثيل جديد لملف`XmpPacketWrapper` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | يحصل على تعليمات معالجة الرأس. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | يحصل على تعريف XMP. اختياري. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | يحصل على مجموعة من[`XmpPackage`](../xmppackage/) داخل XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | الحصول على كمية الحزم داخل بنية XMP . |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | يحصل على تعليمات معالجة المقطورة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | يضيف الحزمة . |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | يزيل الكل[`XmpPackage`](../xmppackage/) داخل XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | تحديد ما إذا كانت الحزمة موجودة في مغلّف xmp. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | يحصل على الحزمة حسب مساحة الاسم URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | يزيل حزمة XMP . |

### ملاحظات

يمكن وضع غلاف يتكون من زوج من تعليمات معالجة XML (PIs) حول rdf: عنصر RDF .

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* المجسم [Aspose.PSD](../../)


