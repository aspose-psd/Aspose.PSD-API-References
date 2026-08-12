---
title: "PsdImage.AddRegularLayer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método PsdImage. Añade una nueva capa regular"
type: docs
weight: 440
url: /es/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
{{< psd/tize >}}
## PsdImage.AddRegularLayer method

Añade una nueva capa regular.

```csharp
public Layer AddRegularLayer()
```

### Valor devuelto

Capa regular creada.

## Ejemplos

El siguiente código muestra cómo añadir la capa regular recién generada a PsdImage.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // Preparando dos matrices de enteros
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

    // Guardar psd
    im.Save(exportPath, new PsdOptions());

    // Guardar png
    im.Save(exportPathPng, new PngOptions());
}
```

### Ver también

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


