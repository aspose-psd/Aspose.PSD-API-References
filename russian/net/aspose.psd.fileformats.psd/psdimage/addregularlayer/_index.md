---
title: PsdImage.AddRegularLayer
second_title: Справочник по Aspose.PSD для .NET API
description: PsdImage метод. Добавляет новый обычный слой.
type: docs
weight: 410
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
## PsdImage.AddRegularLayer method

Добавляет новый обычный слой.

```csharp
public Layer AddRegularLayer()
```

### Возвращаемое значение

Создан обычный слой.

### Примеры

В следующем коде показано, как добавить только что сгенерированный обычный слой в PsdImage.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // Подготовка двух массивов целых чисел
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

    // Сохранить psd
    im.Save(exportPath, new PsdOptions());

    // Сохранить png
    im.Save(exportPathPng, new PngOptions());
}
```

### Смотрите также

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* сборка [Aspose.PSD](../../../)


