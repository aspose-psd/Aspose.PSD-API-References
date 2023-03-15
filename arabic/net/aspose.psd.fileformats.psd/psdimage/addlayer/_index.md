---
title: PsdImage.AddLayer
second_title: Aspose.PSD لمرجع .NET API
description: PsdImage طريقة. يضيف الطبقة .
type: docs
weight: 370
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

يضيف الطبقة .

```csharp
public void AddLayer(Layer layer)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| layer | Layer | طبقة. |

### أمثلة

يوضح المثال التالي كيف يمكنك الرسم على طبقة تم إنشاؤها حديثًا إذا تم استخدام إصدار المُنشئ البسيط في Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // رسم مستطيل باستخدام أداة القلم
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // ارسم مستطيلاً آخر باستخدام فرشاة صلبة باللون الأزرق
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### أنظر أيضا

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)


