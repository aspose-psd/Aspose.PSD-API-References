---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD for .NET API Reference"
description: "Layer メソッド。レイヤーマスクをレイヤーに適用し、マスクを削除します"
type: docs
weight: 350
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

レイヤーマスクをレイヤーに適用し、マスクを削除します。

```csharp
public void ApplyLayerMask()
```

## 例

以下のコードは、レイヤーにマスクを適用する機能を示しています。

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

### 関連項目

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


