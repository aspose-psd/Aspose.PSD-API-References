---
title: Class PathGradientBrush
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Brushes.PathGradientBrush クラス. をカプセル化しますBrushグラデーションのあるオブジェクトこのクラスは継承できません.
type: docs
weight: 170
url: /ja/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

をカプセル化します[`Brush`](../../aspose.psd/brush/)グラデーションのあるオブジェクト。このクラスは継承できません.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | の新しいインスタンスを初期化します`PathGradientBrush`指定されたパスを持つクラス. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | の新しいインスタンスを初期化します`PathGradientBrush`指定されたポイントを持つクラス. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | の新しいインスタンスを初期化します`PathGradientBrush`指定されたポイントを持つクラス. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | の新しいインスタンスを初期化します`PathGradientBrush`指定されたポイントとラップ モードを持つクラス. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | の新しいインスタンスを初期化します`PathGradientBrush`指定されたポイントとラップ モードを持つクラス. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | を取得または設定します[`Blend`](../../aspose.psd/blend/)グラデーションのカスタム減衰を定義する位置と係数を指定します。 |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | パス グラデーションの中心の色を取得または設定します。 |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | パスのグラデーションの中心点を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | グラデーション フォールオフのフォーカス ポイントを取得または設定します。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | このブラシが作成されたグラフィック パスを取得します。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。たとえば、変換マトリックスを設定するか、変換マトリックスを変更するメソッドのいずれかを呼び出す 。このプロパティは、GDI+. との後方互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。値 0 はブラシが完全に表示されることを意味し、値 1 はブラシが完全に不透明であることを意味します。 |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | このブラシが作成されたパス ポイントを取得します。 |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | このパスのポイントに対応する色の配列を取得または設定します`PathGradientBrush`fills. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | コピーを取得または設定します[`Matrix`](../../aspose.psd/matrix/)このための局所的な幾何学的変換を定義する[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | を取得または設定します[`WrapMode`](../../aspose.psd/wrapmode/)このラップモードを示す列挙[`TransformBrush`](../transformbrush/) . |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 現在の新しいディープ クローンを作成します。[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | を乗算します。[`Matrix`](../../aspose.psd/matrix/)これは、この局所的な幾何学的変換を表します[`LinearGradientBrush`](../lineargradientbrush/)指定された[`Matrix`](../../aspose.psd/matrix/)指定された[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | を乗算します。[`Matrix`](../../aspose.psd/matrix/)これは、この局所的な幾何学的変換を表します[`LinearGradientBrush`](../lineargradientbrush/)指定された[`Matrix`](../../aspose.psd/matrix/)指定された順序で. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | をリセットします[`Transform`](../transformbrush/transform/)プロパティからidentity. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 指定された量だけローカル ジオメトリック トランスフォームを回転させます。このメソッドは、変換の前に回転を追加します. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 指定された順序で、指定された量だけローカル ジオメトリック トランスフォームを回転させます。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 指定した量だけローカル ジオメトリック トランスフォームをスケーリングします。このメソッドは、スケーリング マトリックスを変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 指定された順序で、指定された量だけローカル ジオメトリック トランスフォームをスケーリングします。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 中心の色と周囲の 1 つの色への線形減衰を使用してグラデーションを作成します。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 中心の色と周囲の各色への線形減衰を使用してグラデーションを作成します。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | パスの中心から外側に向かってパスの境界に向かって色が変化するグラデーション ブラシを作成します。ある色から別の色への移行は、ベル型の曲線に基づいています. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | パスの中心から外側に向かってパスの境界に向かって色が変化するグラデーション ブラシを作成します。ある色から別の色への移行は、ベル型の曲線に基づいています. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 指定された次元でローカル ジオメトリック トランスフォームを変換します。このメソッドは、transform. の先頭に翻訳を追加します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 指定された順序で、指定された次元でローカル ジオメトリック トランスフォームを変換します。 |

### 備考

中央の色はデフォルトで白です。ユーザーは、後でいつでもこの値を変更できます。

周囲の色の配列は、デフォルトで白色を含む単一の要素によって初期化されます。周囲の色は後で変更できますが、周囲の色を設定するには、少なくとも 1 つの要素が必要です。

を参照してください[`Blend`](./blend/)初期化の詳細については、

### 関連項目

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* 名前空間 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 組み立て [Aspose.PSD](../../)


