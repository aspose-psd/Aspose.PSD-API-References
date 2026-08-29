---
title: "AiImage.SetPalette"
second_title: "Aspose.PSD for .NET API Reference"
description: "AiImage メソッド。画像のパレットを設定します"
type: docs
weight: 200
url: /ja/net/aspose.psd.fileformats.ai/aiimage/setpalette/
---
{{< psd/tize >}}
## AiImage.SetPalette method

画像のパレットを設定します。

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パレット | IColorPalette | 設定するパレットです。 |
| updateColors | Boolean | `true` に設定した場合、色は新しいパレットに従って更新されます；それ以外の場合、カラーインデックスは変更されません。注意: 変更されないインデックスは、対応するパレットエントリがない場合、画像のロード時にクラッシュする可能性があります。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| NotImplementedException | 未実装 |

### 関連項目

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


