---
title: "Класс VstkResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VstkResource класс. Класс ресурса VstkResource. Содержит информацию о данных векторного штриха. Ресурс должен быть инициализирован либо методом AssignItems из ResourceLoader, либо присвоением значений свойствам класса."
type: docs
weight: 3440
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---
{{< psd/tize >}}
## VstkResource class

Класс ресурса VstkResource. Содержит информацию о данных векторной обводки. Ресурс должен быть инициализирован либо методом AssignItems из ResourceLoader, либо присвоением значений свойствам класса.

```csharp
public class VstkResource : LayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VstkResource](vstkresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FillEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillenabled/) { get; set; } | Получает или задает значение, указывающее, включена ли заливка штриха. |
| [FillSettings](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillsettings/) { get; set; } | Получает или задает параметры заполнения обводки. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |
| [StrokeEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokeenabled/) { get; set; } | Получает или задает значение, указывающее, включен ли эффект штриха. |
| [StrokeStyleBlendMode](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleblendmode/) { get; set; } | Получает или задает режим смешивания штриха. |
| [StrokeStyleContent](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylecontent/) { get; set; } | Получает или задает сущность штриха. Свойство определяет настройки заливки штриха. |
| [StrokeStyleLineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/) { get; set; } | Получает или задает выравнивание линии стиля обводки. |
| [StrokeStyleLineCapType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecaptype/) { get; set; } | Получает или задает тип окончания линии стиля штриха. |
| [StrokeStyleLineCapWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecapwidth/) { get; set; } | Получает или задает ширину окончания линии штриха. |
| [StrokeStyleLineDashOffset](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashoffset/) { get; set; } | Получает или задает смещение пунктирной линии стиля штриха. |
| [StrokeStyleLineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashset/) { get; set; } | Получает или задает массив пунктиров линии. |
| [StrokeStyleLineJoinType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinejointype/) { get; set; } | Получает или задает тип соединения линий стиля штриха. |
| [StrokeStyleLineWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/) { get; set; } | Получает или задает ширину линии штриха. |
| [StrokeStyleMiterLimit](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylemiterlimit/) { get; set; } | Получает или задает предельное значение среза (miter) стиля штриха. |
| [StrokeStyleOpacity](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleopacity/) { get; set; } | Получает или задает непрозрачность стиля штриха (0-100%). |
| [StrokeStyleResolution](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleresolution/) { get; set; } | Получает или задает разрешение стиля штриха. |
| [StrokeStyleScaleLock](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylescalelock/) { get; set; } | Получает или задает блокировку масштабирования стиля штриха. |
| [StrokeStyleStrokeAdjust](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylestrokeadjust/) { get; set; } | Получает или задает корректировку штриха. |
| [StrokeStyleVersion](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleversion/) { get; set; } | Получает или задает версию стиля штриха. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/typetoolkey/) | Ключ информации о типе инструмента. |

## Примеры

Следующий код демонстрирует поддержку ресурса VstkResource.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### См. также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


