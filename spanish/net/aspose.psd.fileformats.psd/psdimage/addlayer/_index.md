---
title: "PsdImage.AddLayer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método PsdImage. Añade la capa"
type: docs
weight: 390
url: /es/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Añade la capa.

```csharp
public void AddLayer(Layer layer)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capa | Capa | La capa. |

## Ejemplos

El siguiente ejemplo muestra cómo puedes dibujar en una capa recién creada si se usa la versión simple del constructor en Aspose.PSD

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

    // dibujar un rectángulo con la herramienta Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dibujar otro rectángulo con Solid Brush en color azul
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Ver también

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


