---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdLoadOptions プロパティ。レイヤーが変更されていない場合に、レンダリング中に元のレイヤー ピクセルを保持するかどうかを取得または設定します。"
type: docs
weight: 20
url: /ja/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

取得または設定するのは、レイヤーが変更されていない場合に、レンダリング中に元のレイヤー ピクセルを保持するかどうかです。

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` は変更されていないレイヤーの元のピクセルを保持します; それ以外は `false`。

## 例

以下のコードは、変更前にレイヤーの自動再描画を防止する新しい動作を示しています。

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

### 関連項目

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


