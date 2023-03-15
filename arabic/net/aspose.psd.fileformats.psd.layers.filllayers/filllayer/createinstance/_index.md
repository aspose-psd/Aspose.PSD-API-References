---
title: FillLayer.CreateInstance
second_title: Aspose.PSD لمرجع .NET API
description: FillLayer طريقة. إنشاء مثيل جديد لملفFillLayer فئة حسب نوع التعبئة.
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

إنشاء مثيل جديد لملف[`FillLayer`](../) فئة حسب نوع التعبئة.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fillType | FillType | نوع طبقة التعبئة. |

### قيمة الإرجاع

إرجاع مثيل جديد من[`FillLayer`](../) فئة حسب نوع التعبئة.

### أمثلة

يوضح المثال التالي كيفية إضافة طبقة نوع FillLayer في وقت التشغيل.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### أنظر أيضا

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* المجسم [Aspose.PSD](../../../)


