---
title: "クラス TextureBrush"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Brushes.TextureBrush クラス。TextureBrush クラスの各プロパティは、画像を使用して形状の内部を塗りつぶす Brush オブジェクトです。このクラスは継承できません"
type: docs
weight: 210
url: /ja/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

`TextureBrush` クラスの各プロパティは、画像を使用して形状の内部を塗りつぶす [`Brush`](../../aspose.psd/brush/) オブジェクトです。このクラスは継承できません。

```csharp
public sealed class TextureBrush : TransformBrush
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | 指定された画像を使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | 指定された画像とバウンディング矩形を使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | 指定された画像とバウンディング矩形を使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | 指定された画像とラップモードを使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | 指定された画像、バウンディング矩形、および画像属性を使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | 指定された画像、バウンディング矩形、および画像属性を使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | 指定された画像、ラップモード、およびバウンディング矩形を使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | 指定された画像、ラップモード、およびバウンディング矩形を使用する `TextureBrush` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | この `TextureBrush` オブジェクトに関連付けられた [`Image`](../../aspose.psd/image/) オブジェクトを取得します。 |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | この `TextureBrush` に関連付けられた [`ImageAttributes`](./imageattributes/) を取得します。 |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | この `TextureBrush` に関連付けられた [`Rectangle`](../../aspose.psd/rectangle/) を取得します。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。例えば、変換行列を設定したり、変換行列を変更するメソッドを呼び出す場合などです。このプロパティは GDI+ との下位互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はブラシが完全に透明であることを意味し、1 の値はブラシが完全に不透明であることを意味します。 |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


