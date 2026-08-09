---
title: "الفئة XmpPacketWrapper"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Xmp.XmpPacketWrapper. تحتوي على حزمة xmp مُسلسلة تشمل الرأس والذيل"
type: docs
weight: 6790
url: /ar/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

يحتوي على حزمة xmp مسلسلة تشمل الرأس والذيل.

```csharp
public class XmpPacketWrapper
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | يُنشئ مثالًا جديدًا من الفئة `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | يُنشئ مثالًا جديدًا من الفئة `XmpPacketWrapper`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | يحصل على تعليمات معالجة الرأس. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | يحصل على بيانات XMP الوصفيّة. اختياري. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | يحصل على مصفوفة من [`XmpPackage`](../xmppackage/) داخل XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | يحصل على عدد الحزم داخل بنية XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | يحصل على تعليمات معالجة الذيل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | يضيف الحزمة. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | يزيل جميع [`XmpPackage`](../xmppackage/) داخل XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | يحدد ما إذا كانت الحزمة موجودة في xmp wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | يحصل على الحزمة حسب مساحة الاسم URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | يزيل حزمة XMP. |

## ملاحظات

يمكن وضع غلاف يتألف من زوج من تعليمات معالجة XML (PIs) حول عنصر rdf:RDF.

### انظر أيضًا

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


