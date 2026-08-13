---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage yöntemi. Katmanı ekler"
type: docs
weight: 390
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Katmanı ekler.

```csharp
public void AddLayer(Layer layer)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| katman | Katman | Katman. |

## Örnekler

Aşağıdaki örnek, Aspose.PSD içinde basit yapıcı sürümü kullanılırsa yeni oluşturulan bir katmanda nasıl çizebileceğinizi gösterir.

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

    // Pen aracıyla bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Mavi renkte Solid Brush ile başka bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


