---
title: "Класс IfxsResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource. Ресурс группы эффектов слоя Ifxs"
type: docs
weight: 2840
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ресурс Ifxs (ресурс эффектов группового слоя)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [IfxsResource](ifxsresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Получает версию дескриптора. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | Ключ информации о типе инструмента. |

## Примеры

Следующий код демонстрирует поддержку IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Пример содержит 2 групповых слоя с эффектами
    // Групповой слой с одним эффектом
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Групповой слой с множеством эффектов
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Получите количество эффектов и проверьте их количество
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Один эффект в групповом слое находится в ресурсе 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Два или более эффектов в групповом слое находятся в ресурсе 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Добавьте третью тень к групповому слою с несколькими эффектами
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### См. также

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


