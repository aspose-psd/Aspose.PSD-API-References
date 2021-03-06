---
title: CreateInstance
second_title: Справочник по Aspose.PSD для .NET API
description: Создайте новый экземпляр классаFillLayeraspose.psd.fileformats.psd.layers.filllayers/filllayerпо типу заливки.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Создайте новый экземпляр класса[`FillLayer`](../../filllayer)по типу заливки.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillType | FillType | Тип слоя заливки. |

### Возвращаемое значение

Возвращает новый экземпляр класса[`FillLayer`](../../filllayer)по типу заливки .

### Примеры

В следующем примере показано, как добавить слой типа FillLayer во время выполнения.

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

### Смотрите также

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype)
* class [FillLayer](../../filllayer)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
