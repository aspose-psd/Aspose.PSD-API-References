---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة IPartialRawDataLoader. تعالج البيانات المحملة"
type: docs
weight: 10
url: /ar/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

يعالج البيانات المحمّلة.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مستطيل | Rectangle | مستطيل البيانات. |
| البيانات | Byte[] | البيانات الخام. |
| البداية | نقطة | نقطة بدء البيانات. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| النهاية | نقطة | نقطة نهاية البيانات. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

يعالج البيانات المحمّلة.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مستطيل | Rectangle | مستطيل البيانات. |
| البيانات | Byte[] | البيانات الخام. |
| البداية | نقطة | نقطة بدء البيانات. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| النهاية | نقطة | نقطة نهاية البيانات. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| loadOptions | LoadOptions | خيارات التحميل. |

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


