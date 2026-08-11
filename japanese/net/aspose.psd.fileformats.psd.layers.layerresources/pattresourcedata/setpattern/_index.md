---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD for .NET API Reference"
description: "PattResourceData メソッド。パターンのピクセルバッファとターゲットサイズを設定し、Width / Height を更新し、デフォルト圧縮モード 0 を使用して保存用データを格納します"
type: docs
weight: 110
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

パターンのピクセルバッファとターゲットサイズを設定し、[`Width`](../width/) / [`Height`](../height/) を更新し、デフォルト圧縮モード (0) を使用して保存用データを格納します。

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | Int32[] | `0xAARRGGBB` 形式の 32 ビットピクセル。 |
| bounds | Rectangle | パターンのピクセル境界。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | ピクセル配列の長さは境界領域と等しくなければなりません。 |

### 関連項目

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


