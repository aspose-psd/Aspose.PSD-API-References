---
title: "クラス ColorMatrix"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ColorMatrix クラス。RGBA 空間の座標を含む 5 x 5 行列を定義します。`ImageAttributes` クラスのいくつかのメソッドは、カラーマトリックスを使用して画像の色を調整します。このクラスは継承できません。"
type: docs
weight: 350
url: /ja/net/aspose.psd/colormatrix/
---
{{< psd/tize >}}
## ColorMatrix class

RGBA 空間の座標を含む 5 x 5 行列を定義します。[`ImageAttributes`](../imageattributes/) クラスのいくつかのメソッドは、カラーマトリックスを使用して画像の色を調整します。このクラスは継承できません。

```csharp
public sealed class ColorMatrix
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ColorMatrix](colormatrix/#constructor)() | `ColorMatrix` クラスの新しいインスタンスを初期化します。 |
| [ColorMatrix](colormatrix/#constructor_1)(float[][]) | `ColorMatrix` クラスの新しいインスタンスを、指定されたマトリックス *newColorMatrix* の要素を使用して初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.psd/colormatrix/item/) { get; set; } | `ColorMatrix` の指定された行と列の要素を取得または設定します。 |
| [Matrix00](../../aspose.psd/colormatrix/matrix00/) { get; set; } | この `ColorMatrix` の 0（ゼロ） 行と 0 列の要素を取得または設定します。 |
| [Matrix01](../../aspose.psd/colormatrix/matrix01/) { get; set; } | この `ColorMatrix` の 0（ゼロ） 行と最初の列の要素を取得または設定します。 |
| [Matrix02](../../aspose.psd/colormatrix/matrix02/) { get; set; } | この `ColorMatrix` の 0（ゼロ） 行と2番目の列の要素を取得または設定します。 |
| [Matrix03](../../aspose.psd/colormatrix/matrix03/) { get; set; } | この `ColorMatrix` の 0（ゼロ） 行と3番目の列の要素を取得または設定します。 |
| [Matrix04](../../aspose.psd/colormatrix/matrix04/) { get; set; } | この `ColorMatrix` の 0（ゼロ） 行と4番目の列の要素を取得または設定します。 |
| [Matrix10](../../aspose.psd/colormatrix/matrix10/) { get; set; } | この `ColorMatrix` の最初の行と 0（ゼロ） 列の要素を取得または設定します。 |
| [Matrix11](../../aspose.psd/colormatrix/matrix11/) { get; set; } | この `ColorMatrix` の最初の行と最初の列の要素を取得または設定します。 |
| [Matrix12](../../aspose.psd/colormatrix/matrix12/) { get; set; } | この `ColorMatrix` の最初の行と2番目の列の要素を取得または設定します。 |
| [Matrix13](../../aspose.psd/colormatrix/matrix13/) { get; set; } | この `ColorMatrix` の最初の行と3番目の列の要素を取得または設定します。 |
| [Matrix14](../../aspose.psd/colormatrix/matrix14/) { get; set; } | この `ColorMatrix` の最初の行と4番目の列の要素を取得または設定します。 |
| [Matrix20](../../aspose.psd/colormatrix/matrix20/) { get; set; } | この `ColorMatrix` の2番目の行と 0（ゼロ） 列の要素を取得または設定します。 |
| [Matrix21](../../aspose.psd/colormatrix/matrix21/) { get; set; } | この `ColorMatrix` の2番目の行と最初の列の要素を取得または設定します。 |
| [Matrix22](../../aspose.psd/colormatrix/matrix22/) { get; set; } | この `ColorMatrix` の2番目の行と2番目の列の要素を取得または設定します。 |
| [Matrix23](../../aspose.psd/colormatrix/matrix23/) { get; set; } | この `ColorMatrix` の2番目の行と3番目の列の要素を取得または設定します。 |
| [Matrix24](../../aspose.psd/colormatrix/matrix24/) { get; set; } | この `ColorMatrix` の2番目の行と4番目の列の要素を取得または設定します。 |
| [Matrix30](../../aspose.psd/colormatrix/matrix30/) { get; set; } | この `ColorMatrix` の3番目の行と 0（ゼロ） 列の要素を取得または設定します。 |
| [Matrix31](../../aspose.psd/colormatrix/matrix31/) { get; set; } | この `ColorMatrix` の3番目の行と最初の列の要素を取得または設定します。 |
| [Matrix32](../../aspose.psd/colormatrix/matrix32/) { get; set; } | この `ColorMatrix` の3番目の行と2番目の列の要素を取得または設定します。 |
| [Matrix33](../../aspose.psd/colormatrix/matrix33/) { get; set; } | この `ColorMatrix` の3番目の行と3番目の列の要素を取得または設定します。 |
| [Matrix34](../../aspose.psd/colormatrix/matrix34/) { get; set; } | この `ColorMatrix` の3番目の行と4番目の列の要素を取得または設定します。 |
| [Matrix40](../../aspose.psd/colormatrix/matrix40/) { get; set; } | この `ColorMatrix` の4番目の行と 0（ゼロ） 列の要素を取得または設定します。 |
| [Matrix41](../../aspose.psd/colormatrix/matrix41/) { get; set; } | この `ColorMatrix` の4番目の行と最初の列の要素を取得または設定します。 |
| [Matrix42](../../aspose.psd/colormatrix/matrix42/) { get; set; } | この `ColorMatrix` の第4行第2列の要素を取得または設定します。 |
| [Matrix43](../../aspose.psd/colormatrix/matrix43/) { get; set; } | この `ColorMatrix` の第4行第3列の要素を取得または設定します。 |
| [Matrix44](../../aspose.psd/colormatrix/matrix44/) { get; set; } | この `ColorMatrix` の第4行第4列の要素を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetMatrix](../../aspose.psd/colormatrix/getmatrix/)() | 行列の値を取得します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [MatrixDimensionElementsCount](../../aspose.psd/colormatrix/matrixdimensionelementscount/) | 行列次元の要素数です。 |
| const [MatrixDimensionsCount](../../aspose.psd/colormatrix/matrixdimensionscount/) | 行列の次元数です。 |
| const [MatrixTotalElementsCount](../../aspose.psd/colormatrix/matrixtotalelementscount/) | 行列内の要素の総数です。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


