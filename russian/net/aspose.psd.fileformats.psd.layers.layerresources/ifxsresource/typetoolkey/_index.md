---
title: "IfxsResource.TypeToolKey"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Поле IfxsResource. Ключ информации о типе инструмента"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

Ключ информации о типе инструмента.

```csharp
public const int TypeToolKey;
```

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

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


