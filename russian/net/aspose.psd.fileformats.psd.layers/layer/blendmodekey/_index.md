---
title: "Layer.BlendModeKey"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство Layer. Получает или задает ключ режима смешивания"
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
{{< psd/tize >}}
## Layer.BlendModeKey property

Получает или задает ключ режима смешивания.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### Property Value

Ключ режима смешения.

## Примеры

В следующем примере показано, как использовать режим наложения слоя PassThrough в Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### См. также

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


