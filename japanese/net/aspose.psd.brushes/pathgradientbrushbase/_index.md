---
title: Class PathGradientBrushBase
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Brushes.PathGradientBrushBase クラス. を表しますBrushベースパスグラデーション機能付き.
type: docs
weight: 180
url: /ja/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

を表します[`Brush`](../../aspose.psd/brush/)ベースパスグラデーション機能付き.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | パスのグラデーションの中心点を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | グラデーション フォールオフのフォーカス ポイントを取得または設定します。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | このブラシが作成されたグラフィック パスを取得します。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。たとえば、変換マトリックスを設定するか、変換マトリックスを変更するメソッドのいずれかを呼び出す 。このプロパティは、GDI+. との後方互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。値 0 はブラシが完全に表示されることを意味し、値 1 はブラシが完全に不透明であることを意味します。 |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | このブラシが作成されたパス ポイントを取得します。 |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 指定された次元でローカル ジオメトリック トランスフォームを変換します。このメソッドは、transform. の先頭に翻訳を追加します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 指定された順序で、指定された次元でローカル ジオメトリック トランスフォームを変換します。 |

### 備考

を作成するときは、`PathGradientBrushBase`クラスでは、少なくとも 2 ポイントで初期化する必要があります。内部パス created は常に閉じた図形になり、最後のポイントが最初のポイントに接続されます。その形はこれで満たされています`PathGradientBrushBase`. GDI+ 実装は、OutOfMemoryException同じ座標を持つ空の配列またはポイントセットを渡すとき. `PathGradientBrushBase`ポイント配列に含まれるポイントが 2 つ未満の場合、例外がスローされます。ArgumentException is ではなくスローされますOutOfMemoryExceptionポイント配列が受け入れられない場合. 中心点は、デフォルトで渡されたポイントの重心として計算されます。ユーザーはこのポイントを後で変更できます。

### 関連項目

* class [TransformBrush](../transformbrush/)
* 名前空間 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 組み立て [Aspose.PSD](../../)


