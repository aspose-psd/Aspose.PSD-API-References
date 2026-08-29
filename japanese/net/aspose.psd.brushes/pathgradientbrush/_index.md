---
title: "クラス PathGradientBrush"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Brushes.PathGradientBrush クラス。グラデーションを持つ Brush オブジェクトをカプセル化します。このクラスは継承できません"
type: docs
weight: 170
url: /ja/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

グラデーションを持つ [`Brush`](../../aspose.psd/brush/) オブジェクトをカプセル化します。このクラスは継承できません。

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | 指定されたパスで `PathGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | 指定されたポイントで `PathGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | 指定されたポイントで `PathGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | 指定されたポイントとラップモードで `PathGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | 指定されたポイントとラップモードで `PathGradientBrush` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | グラデーションのカスタムフォールオフを定義する位置と係数を指定する [`Blend`](../../aspose.psd/blend/) を取得または設定します。 |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | パスグラデーションの中心の色を取得または設定します。 |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | パスグラデーションの中心点を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | グラデーションの減衰の焦点を取得または設定します。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | この Brush が基づくグラフィックパスを取得します。 |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | マルチカラー線形グラデーションを定義する [`ColorBlend`](../../aspose.psd/colorblend/) を取得または設定します。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。例えば、変換行列を設定したり、変換行列を変更するメソッドを呼び出す場合などです。このプロパティは GDI+ との下位互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はブラシが完全に透明であることを意味し、1 の値はブラシが完全に不透明であることを意味します。 |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | この Brush が基づくパスのポイントを取得します。 |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | `PathGradientBrush` が塗りつぶすパス内のポイントに対応する色の配列を取得または設定します。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | この [`TransformBrush`](../transformbrush/) のローカル幾何変換を定義するコピー [`Matrix`](../../aspose.psd/matrix/) を取得または設定します。 |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | この [`TransformBrush`](../transformbrush/) のラップモードを示す [`WrapMode`](../../aspose.psd/wrapmode/) 列挙体を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 現在の [`Brush`](../../aspose.psd/brush/) の新しいディープクローンを作成します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | この [`LinearGradientBrush`](../lineargradientbrush/) のローカル幾何変換を表す [`Matrix`](../../aspose.psd/matrix/) に、指定された [`Matrix`](../../aspose.psd/matrix/) を前置して乗算します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | この [`LinearGradientBrush`](../lineargradientbrush/) のローカル幾何変換を表す [`Matrix`](../../aspose.psd/matrix/) に、指定された順序で指定された [`Matrix`](../../aspose.psd/matrix/) を掛け算します。 |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | [`Transform`](../transformbrush/transform/) プロパティを単位行列にリセットします。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に追加します。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ回転させます。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 中心色と1つの周囲色への線形減衰を持つグラデーションを作成します。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 中心色と各周囲色への線形減衰を持つグラデーションを作成します。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | パスの中心から外側の境界まで色が変化するグラデーションブラシを作成します。色の遷移はベル型曲線に基づいています。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | パスの中心から外側の境界まで色が変化するグラデーションブラシを作成します。色の遷移はベル型曲線に基づいています。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に追加します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された寸法だけ平行移動します。 |

## 備考

中心色はデフォルトで白です。ユーザーは後でいつでもこの値を変更できます。

周囲色配列はデフォルトで白色を含む単一要素で初期化されます。周囲色は後で変更可能ですが、設定時には少なくとも1つの要素が必要です。

初期化の詳細については [`Blend`](./blend/) を参照してください。

### 関連項目

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


