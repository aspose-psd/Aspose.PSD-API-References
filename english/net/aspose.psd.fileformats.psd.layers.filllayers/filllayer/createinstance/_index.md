---
title: FillLayer.CreateInstance
second_title: Aspose.PSD for .NET API Reference
description: FillLayer method. Build a new instance of the FillLayer class by type of fill
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Build a new instance of the [`FillLayer`](../) class by type of fill.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fillType | FillType | The type of fill layer. |

### Return Value

Returns a new instance of the [`FillLayer`](../) class by type of fill.

## Examples

The following example demonstrates how to add the FillLayer type layer at runtime.

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

### See Also

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* assembly [Aspose.PSD](../../../)


