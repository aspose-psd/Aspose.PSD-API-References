---
title: "PsdImage.Rotate"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод PsdImage. Поворачивает изображение вокруг центра"
type: docs
weight: 670
url: /ru/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Поворачивает изображение вокруг центра.

```csharp
public override void Rotate(float angle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | Single | Угол поворота в градусах. Положительные значения вращают по часовой стрелке. |

## Примеры

Следующий код демонстрирует возможность вращения изображения на заданный угол.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Вращение всего изображения
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Вращение слоя
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### См. также

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Поворачивает изображение вокруг центра.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | Single | Угол поворота в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | Boolean | если установить `true`, размер изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет повернуто только внутреннее содержимое изображения. |
| backgroundColor | Color | Цвет фона. |

### См. также

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


