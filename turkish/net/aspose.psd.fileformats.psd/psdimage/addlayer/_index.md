---
title: PsdImage.AddLayer
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage yöntem. Katmanı ekler.
type: docs
weight: 370
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Katmanı ekler.

```csharp
public void AddLayer(Layer layer)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| layer | Layer | Katman. |

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de basit kurucu sürümü kullanılıyorsa yeni oluşturulmuş bir katman üzerinde nasıl çizim yapabileceğinizi gösterir.

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

    // Kalem aracıyla bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Düz Fırça ile Mavi renkte başka bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Ayrıca bakınız

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)


