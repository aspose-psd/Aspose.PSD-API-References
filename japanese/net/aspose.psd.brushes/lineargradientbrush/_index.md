---
title: "クラス LinearGradientBrush"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Brushes.LinearGradientBrush クラス。線形グラデーションを持つ Brush をカプセル化します。このクラスは継承できません"
type: docs
weight: 140
url: /ja/net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

線形グラデーションを持つ [`Brush`](../../aspose.psd/brush/) をカプセル化します。このクラスは継承できません。

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | `LinearGradientBrush` クラスの新しいインスタンスをデフォルト パラメータで初期化します。開始色は black、終了色は white、角度は 45 度で、矩形は (0,0) に位置し、サイズは (1,1) です。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | `LinearGradientBrush` クラスの新しいインスタンスを指定されたポイントと色で初期化します。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | `LinearGradientBrush` クラスの新しいインスタンスを指定されたポイントと色で初期化します。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | `LinearGradientBrush` クラスの新しいインスタンスを矩形、開始色と終了色、および方向角度に基づいて初期化します。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | `LinearGradientBrush` クラスの新しいインスタンスを矩形、開始色と終了色、および方向角度に基づいて初期化します。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | `LinearGradientBrush` クラスの新しいインスタンスを矩形、開始色と終了色、および方向角度に基づいて初期化します。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | `LinearGradientBrush` クラスの新しいインスタンスを矩形、開始色と終了色、および方向角度に基づいて初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | グラデーションの角度を取得または設定します。 |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | グラデーションのカスタムフォールオフを定義する位置と係数を指定する [`Blend`](../../aspose.psd/blend/) を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | 終了グラデーション色を取得または設定します。 |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | この [`LinearGradientBrushBase`](../lineargradientbrushbase/) に対してガンマ補正が有効かどうかを示す値を取得または設定します。 |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | マルチカラー線形グラデーションを定義する [`ColorBlend`](../../aspose.psd/colorblend/) を取得または設定します。 |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | この [`LinearGradientBrushBase`](../lineargradientbrushbase/) と共に変換中に [`Angle`](../lineargradientbrushbase/angle/) が変更されるかどうかを示す値を取得または設定します。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。例えば、変換行列を設定したり、変換行列を変更するメソッドを呼び出す場合などです。このプロパティは GDI+ との下位互換性のために導入されました。 |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | グラデーションの開始色と終了色を取得または設定します。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はブラシが完全に透明であることを意味し、1 の値はブラシが完全に不透明であることを意味します。 |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | グラデーションの開始点と終了点を定義する矩形領域を取得または設定します。 |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | 開始グラデーション色を取得または設定します。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | この [`TransformBrush`](../transformbrush/) のローカル幾何変換を定義するコピー [`Matrix`](../../aspose.psd/matrix/) を取得または設定します。 |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | この [`TransformBrush`](../transformbrush/) のラップモードを示す [`WrapMode`](../../aspose.psd/wrapmode/) 列挙体を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 現在の [`Brush`](../../aspose.psd/brush/) の新しいディープクローンを作成します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | この `LinearGradientBrush` のローカル幾何変換を表す [`Matrix`](../../aspose.psd/matrix/) に、指定された [`Matrix`](../../aspose.psd/matrix/) を前置して乗算します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | この `LinearGradientBrush` のローカル幾何変換を表す [`Matrix`](../../aspose.psd/matrix/) に、指定された順序で指定された [`Matrix`](../../aspose.psd/matrix/) を乗算します。 |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | [`Transform`](../transformbrush/transform/) プロパティを単位行列にリセットします。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に追加します。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ回転させます。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 中心色と両端の単一色への線形フォールオフを持つ線形グラデーションを作成します。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 中心色と両端の単一色への線形フォールオフを持つ線形グラデーションを作成します。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | ベル形曲線に基づくグラデーションフォールオフを作成します。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | ベル形曲線に基づくグラデーションフォールオフを作成します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に追加します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された寸法だけ平行移動します。 |

### 関連項目

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


