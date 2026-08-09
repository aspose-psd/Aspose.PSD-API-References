---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة FillLayer. بناء نسخة جديدة من فئة FillLayer حسب نوع التعبئة"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

بناء نسخة جديدة من الفئة [`FillLayer`](../) حسب نوع التعبئة.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fillType | FillType | نوع طبقة التعبئة. |

### قيمة الإرجاع

يعيد نسخة جديدة من الفئة [`FillLayer`](../) حسب نوع التعبئة.

## أمثلة

المثال التالي يوضح كيفية إضافة طبقة من نوع FillLayer أثناء التشغيل.

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

### انظر أيضًا

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


