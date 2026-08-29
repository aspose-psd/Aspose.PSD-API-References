---
title: "クラス Matrix"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Matrix クラス。GDI Matrix の代替です"
type: docs
weight: 5580
url: /ja/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

GDI+ マトリックスを置き換えます。

```csharp
public class Matrix
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Matrix](matrix/#constructor)() | Matrix クラスの新しいインスタンスを単位行列として初期化します。 |
| [Matrix](matrix/#constructor_1)(Matrix) | `Matrix` クラスのコピーを作成します。 |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | 指定された矩形と点の配列で定義された幾何変換に対して、`Matrix` クラスの新しいインスタンスを初期化します。 |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | 指定された矩形と点の配列で定義された幾何変換に対して、`Matrix` クラスの新しいインスタンスを初期化します。 |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | `Matrix` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | この `Matrix` の要素を表す浮動小数点値の配列を取得します。 |
| [M11](../../aspose.psd/matrix/m11/) { get; } | 最初の行・最初の列の行列要素を取得します。X 軸方向のスケールを表します。 |
| [M12](../../aspose.psd/matrix/m12/) { get; } | 最初の行・2 番目の列の行列要素を取得します。Y 軸方向のせん断を表します。 |
| [M21](../../aspose.psd/matrix/m21/) { get; } | 2 行目・最初の列の行列要素を取得します。X 軸方向のせん断を表します。 |
| [M22](../../aspose.psd/matrix/m22/) { get; } | 2 行目・2 列目の行列要素を取得します。Y 軸方向のスケールを表します。 |
| [M31](../../aspose.psd/matrix/m31/) { get; } | 3 行目・最初の列の行列要素を取得します。X 軸方向の平行移動を表します。 |
| [M32](../../aspose.psd/matrix/m32/) { get; } | 3 行目・最初の列の行列要素を取得します。Y 軸方向の平行移動を表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | 指定された Object がこのインスタンスと等しいかどうかを判断します。 |
| [GetElements](../../aspose.psd/matrix/getelements/)() | 行列要素のコピーを取得します。 |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | この Matrix を、matrix パラメーターで指定された行列と (デフォルトの) Prepend 順序で掛け算します。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | この Matrix を、matrix パラメーターで指定された行列と、order パラメーターで指定された順序で掛け算します。 |
| [Reset](../../aspose.psd/matrix/reset/)() | この Matrix を単位行列の要素にリセットします。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | この Matrix に対して、デフォルト（Prepend）順序で、原点（x と y が 0 の座標）を中心に、angle パラメーターで指定された量だけ時計回りに回転させます。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | この Matrix に対して、指定された順序で、原点（x と y が 0 の座標）を中心に、angle パラメーターで指定された量だけ時計回りに回転させます。 |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | この Matrix に対して、デフォルト（Prepend）順序で、指定された点を中心に時計回りに回転させます。 |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | この Matrix に対して、指定された順序で、指定された点を中心に時計回りに回転させます。 |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | この Matrix に対して、（デフォルト）Prepend 順序で、指定されたスケールベクトル（scaleX と scaleY）を適用します。 |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | この `Matrix` に対して、指定された順序で、指定されたスケールベクトル（scaleX と scaleY）を適用します。 |
| override [ToString](../../aspose.psd/matrix/tostring/)() | このインスタンスを表すStringを返します。 |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | この `Matrix` が表す幾何変換を、指定された点の配列に適用します。 |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | この `Matrix` に対して、（デフォルト）Prepend 順序で、指定された平行移動ベクトルを適用します。 |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | この Matrix に対して、指定された順序で、指定された平行移動ベクトルを適用します。 |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | 2 つの行列が等しいかどうかを判定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットが示す変換に加えて、ある軸についての鏡像反転を行い、通常の右手系座標系を左手系に変換することを示します。右手系座標系とは、正の X 軸が反時計回りに回転して正の Y 軸に重なる系で、右手の親指を見たときに指がカールする方向に相当します。左手系座標系とは、正の X 軸が時計回りに回転して正の Y 軸に重なる系で、左手の指がカールする方向に相当します。元の反転や鏡像変換の角度を数学的に決定する方法はなく、適切な調整回転があればすべての反転角度は同一です。NOTE: TypeFlip は GENERAL_TRANSFORM が公開された後に追加されたため、フラグビットを便利に再番号付けすることができず、外部コードとのバイナリ互換性が失われる恐れがあります。 |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットが示す変換に加えて、任意の角度で回転を行うことを示します。回転はベクトルの元の方向に関係なく、ベクトルの角度を同じ量だけ変え、ベクトルの長さは変えません。このフラグビットは、 |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | 一般的なスケールは、ベクトルの長さを x 方向と y 方向で異なる量だけ乗算し、直交ベクトル間の角度は変えません。このフラグビットは TypeUniformScale フラグと相互排他的です。 |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | この定数は、このオブジェクトで定義された変換が入力座標の任意の変換を行うことを示します。上記の定数のいずれかでこの変換を分類できる場合、タイプは定数 TypeIdentity になるか、またはこの変換が実行するさまざまな座標変換に対応するフラグビットの組み合わせになります。 |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | 単位変換とは、出力座標が常に入力座標と同じである変換です。この変換が単位変換以外である場合、タイプは定数 GENERAL_TRANSFORM になるか、またはこの変換が実行するさまざまな座標変換に対応するフラグビットの組み合わせになります。 |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | この定数は、回転フラグビットのいずれかに対するビットマスクです。 |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | この定数は、スケールフラグビットのいずれかに対するビットマスクです。 |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットが示す変換に加えて、90 度の倍数だけの象限回転を行うことを示します。回転はベクトルの元の方向に関係なく、ベクトルの角度を同じ量だけ変え、ベクトルの長さは変えません。このフラグビットは TypeGeneralRotation フラグと相互排他的です。 |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | 平行移動は、ベクトルの長さや角度を変えずに、x と y の座標を一定量だけ移動させます。 |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | 均一スケールは、ベクトルの長さを x 方向と y 方向の両方で同じ量だけ乗算し、ベクトル間の角度は変えません。このフラグビットは TypeGeneralScale フラグと相互排他的です。 |

## 備考

ほとんどのアルゴリズムは Sun の AffineTransform.java から取られています。内部で使用される行列要素の Java 名と .NET 名の対応表: m00 M11 スケール X, m10 M12 シアー Y, m01 M21 シアー X, m11 M22 スケール Y, m02 M31 平行移動 X, m12 M32 平行移動 Y

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


