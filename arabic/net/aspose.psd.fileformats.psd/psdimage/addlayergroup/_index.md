---
title: "PsdImage.AddLayerGroup"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. يضيف مجموعة الطبقات"
type: docs
weight: 400
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
{{< psd/tize >}}
## PsdImage.AddLayerGroup method

يضيف مجموعة الطبقة.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| groupName | String | اسم المجموعة. |
| فهرس | Int32 | فهرس الطبقة التي سيتم الإدراج بعدّها. |
| startBehaviour | Boolean | إذا تم تعيينه إلى `true` [start behaviour] فإن المجموعة ستكون في حالة مفتوحة عند بدء التشغيل، وإلا ستكون في حالة مصغرة. |

### قيمة الإرجاع

فتح طبقة المجموعة

### استثناءات

| استثناء | شرط |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | يجب أن يكون الفهرس ضمن حدود عدد الطبقات |

### انظر أيضًا

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


