---
title: "PsdImage.AddRegularLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. يضيف طبقة عادية جديدة"
type: docs
weight: 440
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
{{< psd/tize >}}
## PsdImage.AddRegularLayer method

يضيف طبقة عادية جديدة.

```csharp
public Layer AddRegularLayer()
```

### قيمة الإرجاع

تم إنشاء طبقة عادية.

## أمثلة

الكود التالي يوضح كيفية إضافة الطبقة العادية التي تم إنشاؤها حديثًا إلى PsdImage.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // تحضير مصفوفتين من النوع int
    var data1 = new int[2500];
    var data2 = new int[2500];

    var rect1 = new Rectangle(0, 0, 50, 50);
    var rect2 = new Rectangle(0, 0, 100, 25);

    for (int i = 0; i < 2500; i++)
    {
        data1[i] = -10000000;
        data2[i] = -10000000;
    }

    var layer1 = im.AddRegularLayer();
    layer1.Left = 25;
    layer1.Top = 25;
    layer1.Right = 75;
    layer1.Bottom = 75;
    layer1.SaveArgb32Pixels(rect1, data1);

    var layer2 = im.AddRegularLayer();
    layer2.Left = 25;
    layer2.Top = 150;
    layer2.Right = 125;
    layer2.Bottom = 175;
    layer2.SaveArgb32Pixels(rect2, data2);

    // احفظ psd
    im.Save(exportPath, new PsdOptions());

    // احفظ png
    im.Save(exportPathPng, new PngOptions());
}
```

### انظر أيضًا

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


