---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية IGradientFillSettings. يحصل أو يعيّن مقياس التدرج الطبيعي بالنسبة المئوية"
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

يحصل أو يعيّن مقياس التدرج **المُعَدَّل** (بالنسبة المئوية).

```csharp
public int Scale { get; set; }
```

### Property Value

المقياس.

## أمثلة

المثال التالي يوضح كيفية استخدام خاصية Scale لتكبير FillLayer بالتدرج.

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

    // تحديث قيمة المقياس
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### انظر أيضًا

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


