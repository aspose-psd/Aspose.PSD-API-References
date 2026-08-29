---
title: "Layer.ApplyLayerMask"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Layer. Применяет маску слоя к слою, затем удаляет маску"
type: docs
weight: 350
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Применяет маску слоя к слою, затем удаляет маску.

```csharp
public void ApplyLayerMask()
```

## Примеры

Следующий код демонстрирует возможность применения маски к слою.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


