---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. تضيف الطبقة"
type: docs
weight: 390
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

يضيف الطبقة.

```csharp
public void AddLayer(Layer layer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| طبقة | طبقة | الطبقة. |

## أمثلة

المثال التالي يوضح كيف يمكنك الرسم على طبقة تم إنشاؤها حديثًا إذا تم استخدام نسخة المنشئ البسيطة في Aspose.PSD.

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

    // ارسم مستطيلًا بأداة القلم
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // ارسم مستطيلًا آخر بفرشاة صلبة باللون الأزرق
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### انظر أيضًا

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


