---
title: "FillLayer.CreateInstance"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод FillLayer. Создаёт новый экземпляр класса FillLayer по типу заливки."
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Создайте новый экземпляр класса [`FillLayer`](../) по типу заливки.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillType | FillType | Тип слоя заливки. |

### Возвращаемое значение

Возвращает новый экземпляр класса [`FillLayer`](../) по типу заливки.

## Примеры

Следующий пример демонстрирует, как добавить слой типа FillLayer во время выполнения.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### См. также

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


