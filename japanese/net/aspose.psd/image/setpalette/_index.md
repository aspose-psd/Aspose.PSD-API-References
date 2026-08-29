---
title: "Image.SetPalette"
second_title: "Aspose.PSD for .NET API Reference"
description: "Image メソッド。画像のパレットを設定します。"
type: docs
weight: 250
url: /ja/net/aspose.psd/image/setpalette/
---
{{< psd/tize >}}
## Image.SetPalette method

画像のパレットを設定します。

```csharp
public abstract void SetPalette(IColorPalette palette, bool updateColors)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パレット | IColorPalette | 設定するパレットです。 |
| updateColors | Boolean | `true` に設定した場合、色は新しいパレットに従って更新されます；それ以外の場合、カラーインデックスは変更されません。注意: 変更されないインデックスは、対応するパレットエントリがない場合、画像のロード時にクラッシュする可能性があります。 |

### 関連項目

* interface [IColorPalette](../../icolorpalette/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


