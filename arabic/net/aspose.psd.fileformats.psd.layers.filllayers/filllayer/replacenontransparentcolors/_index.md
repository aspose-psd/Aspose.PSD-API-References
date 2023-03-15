---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD لمرجع .NET API
description: FillLayer طريقة. يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة إذا كنت تستخدمها على صور بدون شفافية  فسيتم استبدال كل الألوان بأخرى.
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بأخرى.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newColorArgb | Int32 | قيمة ARGB الجديدة للون لاستبدال الألوان غير الشفافة بـ. |

### أمثلة

توضح التعليمة البرمجية التالية دعم CMYK ColorMode 16 بت والقدرة على الرسم باستخدام فئة Aspose.PSD.Graphics.

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### أنظر أيضا

* class [FillLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* المجسم [Aspose.PSD](../../../)


