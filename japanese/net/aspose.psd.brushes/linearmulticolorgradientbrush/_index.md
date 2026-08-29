---
title: "クラス LinearMulticolorGradientBrush"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Brushes.LinearMulticolorGradientBrush クラス。複数の色と適切な位置で定義された線形グラデーションを持つブラシを表します。このクラスは継承できません"
type: docs
weight: 160
url: /ja/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

複数の色と適切な位置で定義された線形グラデーションを持つ [`Brush`](../../aspose.psd/brush/) を表します。このクラスは継承できません。

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | `LinearMulticolorGradientBrush` クラスの新しいインスタンスをデフォルトパラメーターで初期化します。開始色は黒、終了色は白、角度は 45 度で、矩形は (0,0) に位置しサイズは (1,1) です。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | 指定されたポイントで `LinearMulticolorGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | 指定されたポイントで `LinearMulticolorGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | 矩形と方向角度に基づいて `LinearMulticolorGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | 矩形と方向角度に基づいて `LinearMulticolorGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | 矩形と方向角度に基づいて `LinearMulticolorGradientBrush` クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | 矩形と方向角度に基づいて `LinearMulticolorGradientBrush` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | グラデーションの角度を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | この [`LinearGradientBrushBase`](../lineargradientbrushbase/) に対してガンマ補正が有効かどうかを示す値を取得または設定します。 |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | マルチカラー線形グラデーションを定義する [`ColorBlend`](../../aspose.psd/colorblend/) を取得または設定します。 |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | この [`LinearGradientBrushBase`](../lineargradientbrushbase/) と共に変換中に [`Angle`](../lineargradientbrushbase/angle/) が変更されるかどうかを示す値を取得または設定します。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。例えば、変換行列を設定したり、変換行列を変更するメソッドを呼び出す場合などです。このプロパティは GDI+ との下位互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はブラシが完全に透明であることを意味し、1 の値はブラシが完全に不透明であることを意味します。 |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | グラデーションの開始点と終了点を定義する矩形領域を取得または設定します。 |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に追加します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された寸法だけ平行移動します。 |

### 関連項目

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


