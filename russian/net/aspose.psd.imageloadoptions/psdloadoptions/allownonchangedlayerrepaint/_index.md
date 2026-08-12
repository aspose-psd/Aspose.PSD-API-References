---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PsdLoadOptions. Получает или задает, сохранять ли оригинальные пиксели слоёв при рендеринге, если слой не был изменён"
type: docs
weight: 20
url: /ru/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Получает или задает, сохранять ли оригинальные пиксели слоёв во время рендеринга, если слой не был изменён.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true`, чтобы сохранить оригинальные пиксели неизменённых слоёв; иначе `false`.

## Примеры

Следующий код демонстрирует новое поведение, которое предотвращает автоматическую перерисовку слоёв до внесения изменений.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### См. также

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


