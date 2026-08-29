---
title: "クラス TransformBrush"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Brushes.TransformBrush クラス。変換機能を持つ Brush"
type: docs
weight: 220
url: /ja/net/aspose.psd.brushes/transformbrush/
---
{{< psd/tize >}}
## TransformBrush class

変換機能を持つ [`Brush`](../../aspose.psd/brush/)。

```csharp
public abstract class TransformBrush : Brush
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。例えば、変換行列を設定したり、変換行列を変更するメソッドを呼び出す場合などです。このプロパティは GDI+ との下位互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はブラシが完全に透明であることを意味し、1 の値はブラシが完全に不透明であることを意味します。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | この `TransformBrush` のローカル幾何変換を定義するコピー [`Matrix`](../../aspose.psd/matrix/) を取得または設定します。 |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | この `TransformBrush` のラップモードを示す [`WrapMode`](../../aspose.psd/wrapmode/) 列挙体を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 現在の [`Brush`](../../aspose.psd/brush/) の新しいディープクローンを作成します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | この [`LinearGradientBrush`](../lineargradientbrush/) のローカル幾何変換を表す [`Matrix`](../../aspose.psd/matrix/) に、指定された [`Matrix`](../../aspose.psd/matrix/) を前置して乗算します。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | この [`LinearGradientBrush`](../lineargradientbrush/) のローカル幾何変換を表す [`Matrix`](../../aspose.psd/matrix/) に、指定された順序で指定された [`Matrix`](../../aspose.psd/matrix/) を掛け算します。 |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | この [`Transform`](./transform/) プロパティを単位変換にリセットします。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に追加します。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ回転させます。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に追加します。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された寸法だけ平行移動します。 |

### 関連項目

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


