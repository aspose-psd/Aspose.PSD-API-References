---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية WarpSettings. تحصل أو تعيين حجم شبكة الالتواء. القيمة الافتراضية هي 1"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

يحصل أو يضبط حجم شبكة الانحراف. القيمة الافتراضية هي 1.

```csharp
public Size GridSize { get; set; }
```

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

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


