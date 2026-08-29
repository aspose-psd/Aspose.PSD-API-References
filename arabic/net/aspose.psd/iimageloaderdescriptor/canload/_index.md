---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة IImageLoaderDescriptor. تحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام *loadOptions* اختياريًا"
type: docs
weight: 10
url: /ar/net/aspose.psd/iimageloaderdescriptor/canload/
---
{{< psd/tize >}}
## IImageLoaderDescriptor.CanLoad method

يحدد ما إذا كان محمِّل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واختياريًا باستخدام *loadOptions*.

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | StreamContainer | حاوية الدفق. |
| loadOptions | LoadOptions | تفاصيل تنسيق الملف المحددة بواسطة *loadOptions*. قد تكون *loadOptions* فارغة. |

### قيمة الإرجاع

`true` إذا كان محمل الصورة الذي أنشئه هذا الوصف يمكنه قراءة الصورة من الدفق؛ وإلا `false`.

### انظر أيضًا

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


