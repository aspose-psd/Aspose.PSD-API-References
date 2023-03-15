---
title: Class LinearGradientBrush
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Brushes.LinearGradientBrush クラス. をカプセル化しますBrush線形グラデーションでこのクラスは継承できません.
type: docs
weight: 140
url: /ja/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

をカプセル化します[`Brush`](../../aspose.psd/brush/)線形グラデーションで。このクラスは継承できません.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | の新しいインスタンスを初期化します`LinearGradientBrush`クラスのデフォルト パラメータ. 開始色は黒、終了色は白、角度は 45 度、四角形は (0,0) に位置し、サイズは (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | の新しいインスタンスを初期化します`LinearGradientBrush`指定されたポイントと色を持つクラス. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | の新しいインスタンスを初期化します`LinearGradientBrush`指定されたポイントと色を持つクラス. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | の新しいインスタンスを初期化します`LinearGradientBrush`長方形、開始色と終了色、および方向角度に基づくクラス. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | の新しいインスタンスを初期化します`LinearGradientBrush`長方形、開始色と終了色、および方向角度に基づくクラス. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | の新しいインスタンスを初期化します`LinearGradientBrush`長方形、開始色と終了色、および方向角度に基づくクラス. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | の新しいインスタンスを初期化します`LinearGradientBrush`長方形、開始色と終了色、および方向角度に基づくクラス. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | グラデーション角度を取得または設定します。 |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | を取得または設定します[`Blend`](../../aspose.psd/blend/)グラデーションのカスタム減衰を定義する位置と係数を指定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | グラデーションの終了色を取得または設定します。 |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | ガンマ補正が有効かどうかを示す値を取得または設定します[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | かどうかを示す値を取得または設定します。[`Angle`](../lineargradientbrushbase/angle/)これで変換中に変更されます[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。たとえば、変換マトリックスを設定するか、変換マトリックスを変更するメソッドのいずれかを呼び出す 。このプロパティは、GDI+. との後方互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。値 0 はブラシが完全に表示されることを意味し、値 1 はブラシが完全に不透明であることを意味します。 |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | グラデーションの開始点と終了点を定義する四角形の領域を取得または設定します。 |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | グラデーションの開始色を取得または設定します。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | コピーを取得または設定します[`Matrix`](../../aspose.psd/matrix/)このための局所的な幾何学的変換を定義する[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | を取得または設定します[`WrapMode`](../../aspose.psd/wrapmode/)このラップモードを示す列挙[`TransformBrush`](../transformbrush/) . |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 現在の新しいディープ クローンを作成します。[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | を乗算します。[`Matrix`](../../aspose.psd/matrix/)これは、この局所的な幾何学的変換を表します`LinearGradientBrush`指定された[`Matrix`](../../aspose.psd/matrix/)指定された[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | を乗算します。[`Matrix`](../../aspose.psd/matrix/)これは、この局所的な幾何学的変換を表します`LinearGradientBrush`指定された[`Matrix`](../../aspose.psd/matrix/)指定された順序で. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | をリセットします[`Transform`](../transformbrush/transform/)プロパティからidentity. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 指定された量だけローカル ジオメトリック トランスフォームを回転させます。このメソッドは、変換の前に回転を追加します. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 指定された順序で、指定された量だけローカル ジオメトリック トランスフォームを回転させます。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 指定した量だけローカル ジオメトリック トランスフォームをスケーリングします。このメソッドは、スケーリング マトリックスを変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 指定された順序で、指定された量だけローカル ジオメトリック トランスフォームをスケーリングします。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 中央の色と両端の単一色への線形フォールオフを持つ線形グラデーションを作成します。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 中央の色と両端の単一色への線形フォールオフを持つ線形グラデーションを作成します。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | ベル型の曲線に基づいてグラデーション フォールオフを作成します。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | ベル型の曲線に基づいてグラデーション フォールオフを作成します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 指定された次元でローカル ジオメトリック トランスフォームを変換します。このメソッドは、transform. の先頭に翻訳を追加します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 指定された順序で、指定された次元でローカル ジオメトリック トランスフォームを変換します。 |

### 関連項目

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* 名前空間 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 組み立て [Aspose.PSD](../../)


