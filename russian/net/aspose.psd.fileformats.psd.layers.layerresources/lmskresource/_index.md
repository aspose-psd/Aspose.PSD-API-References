---
title: "Класс LmskResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource class. Ресурс LMsk"
type: docs
weight: 3020
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

Ресурс LMsk.

```csharp
public class LmskResource : LayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LmskResource](lmskresource/)() | Инициализирует новый экземпляр класса `LmskResource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Получает первый компонент цвета. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Получает второй компонент цвета. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Получает третий компонент цвета. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Получает четвертый компонент цвета. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Получает цветовое пространство. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Получает флаг. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Получает непрозрачность. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | Ключ информации о типе инструмента. |

## Примечания

Этот ресурс содержит идентификатор цветового пространства, который относится к определённому типу цветового пространства, и 4 цветовых компонента. В зависимости от идентификатора, цветовые компоненты имеют разные значения. Если тип цветового пространства не требует четырёх значений, дополнительные компоненты неопределены и всегда записываются нулями. Цветовые компоненты по типам цветовых пространств: RGB - первые три компонента — красный, зелёный и синий. HSB - первые три компонента — оттенок, насыщенность и яркость. CMYK - четыре компонента — циан, маджента, жёлтый и чёрный. Lab - первые три компонента — светлота, a-хроминанс и b-хроминанс. Grayscale - первый компонент — значение серого от 0...10000.

## Примеры

Следующий код демонстрирует, как изменить параметры отображения маски слоя на 16‑битных изображениях, изменяя свойства LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Загрузить 16‑битное изображение.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Найти LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Проверить свойства LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Изменить свойства LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Сохранить изображение.
    image.Save(outputPsd);
}
```

### См. также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


