---
title: Class Matrix
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Matrix クラス. GDI マトリックスを置き換えます
type: docs
weight: 5090
url: /ja/net/aspose.psd/matrix/
---
## Matrix class

GDI+ マトリックスを置き換えます。

```csharp
public class Matrix
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Matrix](matrix/#constructor)() | Matrix クラスの新しいインスタンスを単位行列として初期化します。 |
| [Matrix](matrix/#constructor_1)(Matrix) | のコピーを作成します`Matrix`class. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | の新しいインスタンスを初期化します`Matrix`指定された長方形と点の配列によって定義される幾何学的変換へのクラス. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | の新しいインスタンスを初期化します`Matrix`指定された長方形と点の配列によって定義される幾何学的変換へのクラス. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | の新しいインスタンスを初期化します`Matrix`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | この要素を表す浮動小数点値の配列を取得します`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | 1 行 1 列目の行列要素を取得します。 X 軸に沿ったスケールを表します。 |
| [M12](../../aspose.psd/matrix/m12/) { get; } | 1 行 2 列目の行列要素を取得します。 Y 軸に沿ったせん断を表します。 |
| [M21](../../aspose.psd/matrix/m21/) { get; } | 2 行 1 列の行列要素を取得します。 X 軸に沿ったせん断を表します。 |
| [M22](../../aspose.psd/matrix/m22/) { get; } | 2 行 2 列目の行列要素を取得します。 Y 軸に沿ったスケールを表します。 |
| [M31](../../aspose.psd/matrix/m31/) { get; } | 3 行 1 列目の行列要素を取得します。 X 軸に沿った移動を表します。 |
| [M32](../../aspose.psd/matrix/m32/) { get; } | 3 行 1 列目の行列要素を取得します。 Y 軸に沿った移動を表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | 指定されたObjectこのインスタンスと等しい. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | 行列要素のコピーを取得します。 |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | このインスタンスのハッシュ コードを返します。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | (デフォルト) Prepend order. を使用して、matrix パラメータで指定された行列でこの Matrix を乗算します。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | この Matrix に、matrix パラメータで指定された行列を、order パラメータで指定された順序で乗算します。 |
| [Reset](../../aspose.psd/matrix/reset/)() | 単位行列の要素を持つようにこの行列をリセットします。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | 角度パラメーターで指定された量の時計回りの回転を、この Matrix の原点 (x 座標と y 座標がゼロ) の周りに、デフォルト (プリペンド) の順序で適用します。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | 指定された順序で、この Matrix の原点 (ゼロの x および y 座標) を中心に、角度パラメーターで指定された量の時計回りの回転を適用します。 |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | 指定された点を中心に時計回りの回転をこの Matrix にデフォルト (プリペンド) の順序で適用します. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | 指定された点を中心に時計回りの回転を指定された順序でこの Matrix に適用します。 |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | (デフォルト) Prepend order. を使用して、指定されたスケール ベクトル (scaleX および scaleY) をこの Matrix に適用します。 |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | 指定されたスケール ベクトル (scaleX および scaleY) をこれに適用します`Matrix`指定された order. を使用して |
| override [ToString](../../aspose.psd/matrix/tostring/)() | を返しますStringこのインスタンスを表す. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | これで表される幾何学的変換を適用します`Matrix`ポイントの指定された配列に. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | 指定された平行移動ベクトルをこれに適用します`Matrix`(デフォルト) Prepend order. を使用 |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | 指定された平行移動ベクトルを指定された順序でこの Matrix に適用します。 |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | 2 つの行列が等しいかどうかを判断します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | このフラグ ビットは、この object によって定義された変換が、他のフラグ ビットによって示される変換に加えて、 通常は右利きの座標系を左利きの システムに変更する何らかの軸についてミラー イメージ フリップを実行することを示します。 右利きの座標系正の X 軸が反時計回りに回転して、正の Y 軸 をオーバーレイするものです。これは、右手の指 を凝視したときに親指で終わる方向と同様です. 左手座標系は、正の X 軸が回転する座標系です。正の Y 軸を時計回りに重ねて、左手の指が曲がる方向に似た を重ねます. 元の反転またはミラーリング変換の角度を決定する数学的な方法はありません。 注: TypeFlip は GENERAL_TRANSFORM の後に追加されましたは public 流通しており、outside code. でバイナリの非互換性を導入することなく、フラグ ビットを便利に 再番号付けすることができなくなりました。 |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | このフラグ ビットは、この object によって定義された変換が、他のフラグ ビットによって示される 変換に加えて、任意の角度による回転を実行することを示します。このフラグ ビットは、 と相互に排他的です。 |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | 一般的なスケールは、垂直ベクトル間の角度 を変更せずに、ベクトルの長さに異なる 量を x 方向と y 方向に乗算します. このフラグ ビットは、TypeUniformScale フラグと相互に排他的です. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | この定数は、この object によって定義された変換が、入力座標の任意の変換を実行することを示します。 この変換が上記の定数のいずれかによって分類できる場合、 タイプは、定数 TypeIdentity または適切なフラグの組み合わせ a になります。この変換が実行するさまざまな座標 変換のビット. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | 恒等変換は、出力座標が 常に入力座標と同じである変換です. この変換が恒等変換以外の場合、 タイプは定数 GENERAL_TRANSFORM または適切なフラグ ビットの 組み合わせのいずれかになります。この変換が実行するさまざまな座標 変換. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | この定数は、任意の回転フラグ ビットのビット マスクです。 |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | この定数は、任意のスケール フラグ ビットのビット マスクです。 |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | このフラグ ビットは、この object によって定義された変換が、他のフラグ ビットによって示される変換に加えて、 で 90 度の倍数で象限回転を実行することを示します. 回転は、元の方向に関係なく、同じ量 だけベクトルの角度を変更します。ベクトルの長さを変更せずに . このフラグ ビットは TypeGeneralRotation フラグと相互に排他的です. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | 平行移動は、ベクトルの長さや角度を変更せずに、座標を x および y で一定量だけ移動します。 |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | 均一スケールは、 ベクトル間の角度を変更せずに、x 方向と y 方向の両方で同じ量 でベクトルの長さを乗算します. このフラグ ビットは、TypeGeneralScale フラグと相互に排他的です. |

### 備考

Sun の AffineTransform から取得したほとんどのアルゴリズム.java. 内部で使用される行列要素の Java 名。 X を変換 m12 M32 Y を変換

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


