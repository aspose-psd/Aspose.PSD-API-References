---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة FillLayer. تستبدل جميع الألوان غير الشفافة بلون جديد وتحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة إذا استخدمتها على صور بدون شفافية جميع الألوان سيتم استبدالها بلون واحد"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorArgb | Int32 | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

## أمثلة

الكود التالي يوضح دعم وضع اللون CMYK 16 بت والقدرة على الرسم باستخدام الفئة Aspose.PSD.Graphics.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### انظر أيضًا

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


