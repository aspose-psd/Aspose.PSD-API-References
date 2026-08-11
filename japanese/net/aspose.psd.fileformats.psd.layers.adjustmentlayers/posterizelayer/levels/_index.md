---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD for .NET API Reference"
description: "PosterizeLayer プロパティ。Posterize レイヤーのレベル"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

Posterize レイヤーのレベル。

```csharp
public short Levels { get; set; }
```

## 例

以下のコードは PosterizeLayer のサポートを示しています。

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    foreach (Layer layer in image.Layers)
    {
        if (layer is PosterizeLayer)
        {
            ((PosterizeLayer)layer).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### 関連項目

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


