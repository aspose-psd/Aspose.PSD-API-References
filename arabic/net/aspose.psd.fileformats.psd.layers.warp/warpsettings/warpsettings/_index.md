---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ WarpSettings. يهيئ نسخة جديدة من فئة WarpSettings"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

يهيئ نسخة جديدة من الفئة [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| meshPoints | PointF[] | نقاط الشبكة للالتواء |
| الحدود | Rectangle | حدود صورة الالتواء |

## أمثلة

الكود التالي يوضح دعم خاصية WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // احصل على إعدادات الالتواء
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // عيّن حجمًا جديدًا
    // بالنسبة إلى Photoshop يمكن أن تكون القيمة بين 1 و 50 ولا يمكنك حفظ ملف PSD بشكل صحيح.
    warpSettings.GridSize = new Size(100, 100);

    // عيّن قيمة صالحة
    warpSettings.GridSize = new Size(3, 3);

    // عرض ملف المثال مع شبكة x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### انظر أيضًا

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

يهيئ نسخة جديدة من الفئة [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| meshPoints | PointF[] | نقاط الشبكة للالتواء |
| الحدود | Rectangle | حدود صورة الالتواء |
| style | WarpStyles | نمط الالتواء |

## أمثلة

الكود التالي يوضح دعم خاصية WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // احصل على إعدادات الالتواء
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // عيّن حجمًا جديدًا
    // بالنسبة إلى Photoshop يمكن أن تكون القيمة بين 1 و 50 ولا يمكنك حفظ ملف PSD بشكل صحيح.
    warpSettings.GridSize = new Size(100, 100);

    // عيّن قيمة صالحة
    warpSettings.GridSize = new Size(3, 3);

    // عرض ملف المثال مع شبكة x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### انظر أيضًا

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

يهيئ نسخة جديدة من الفئة [`WarpSettings`](../).

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | عناصر PS مع إعدادات الالتواء |
| الحدود | Rectangle | حدود صورة الالتواء |

### انظر أيضًا

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

يهيئ نسخة جديدة من الفئة [`WarpSettings`](../).

```csharp
public WarpSettings(PlacedResource placedResource)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| placedResource | PlacedResource | المورد مع إعدادات الالتواء |

### انظر أيضًا

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


