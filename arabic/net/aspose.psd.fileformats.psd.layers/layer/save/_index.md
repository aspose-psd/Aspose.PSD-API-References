---
title: "Layer.Save"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Layer. يحفظ بيانات الكائن إلى الدفق المحدد"
type: docs
weight: 390
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

يحفظ بيانات الكائن إلى الدفق المحدد.

```csharp
public override void Save(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لحفظ بيانات الكائن إليه. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | لا ينبغي استدعاء طريقة Save بدون خيارات الصورة |

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| خيارات | ImageOptionsBase | الخيارات. |

### انظر أيضًا

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

يحفظ بيانات الكائن إلى موقع الملف المحدد.

```csharp
public override void Save(string filePath, bool overWrite)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لحفظ بيانات الكائن إليه. |
| overWrite | Boolean | إذا تم تعيينه إلى `true` فستتم كتابة محتويات الملف من جديد، وإلا سيحدث الإلحاق. |

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لحفظ بيانات الصورة إليه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### انظر أيضًا

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| خيارات | ImageOptionsBase | الخيارات. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### انظر أيضًا

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


