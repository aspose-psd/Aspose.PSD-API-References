---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD لمرجع .NET API
description: IGradientFillSettings ملكية. الحصول على المقياس أو تعيينه.
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

الحصول على المقياس أو تعيينه.

```csharp
public int Scale { get; set; }
```

### Property_Value

المقياس .

### أمثلة

يوضح المثال التالي كيفية استخدام خاصية Scale لتوسيع نطاق FillLayer باستخدام التدرج اللوني.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // الحصول على طبقة تعبئة
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // قيمة مقياس التحديث
    settings.Scale = 200;
    fillLayer.Update(); // يحدّث بيانات البكسل

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### أنظر أيضا

* interface [IGradientFillSettings](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* المجسم [Aspose.PSD](../../../)


