---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdImage metod. Lägger till lagret"
type: docs
weight: 390
url: /sv/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Lägger till lagret.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lager | Lager | Lagret. |

## Exempel

Följande exempel visar hur du kan rita på ett nyss skapat lager om den enkla konstruktörsversionen används i Aspose.PSD

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

    // rita en rektangel med Pen-verktyg
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // rita en annan rektangel med Solid Brush i blå färg
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Se även

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


