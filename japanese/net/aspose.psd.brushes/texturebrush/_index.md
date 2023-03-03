---
title: Class TextureBrush
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Brushes.TextureBrush クラス. の各プロパティTextureBrushクラスはBrushイメージを使用して形状の内部を塗りつぶすオブジェクトこのクラスは継承できません.
type: docs
weight: 210
url: /ja/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

の各プロパティ`TextureBrush`クラスは[`Brush`](../../aspose.psd/brush/)イメージを使用して形状の内部を塗りつぶすオブジェクト。このクラスは継承できません.

```csharp
public sealed class TextureBrush : TransformBrush
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | の新しいインスタンスを初期化します`TextureBrush`指定された画像を使用するクラス. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | の新しいインスタンスを初期化します`TextureBrush`指定された画像と外接する四角形を使用するクラス. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | の新しいインスタンスを初期化します`TextureBrush`指定された画像と外接する四角形を使用するクラス. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | の新しいインスタンスを初期化します`TextureBrush`指定されたイメージとラップ モードを使用するクラス. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | の新しいインスタンスを初期化します`TextureBrush`指定された画像、外接する四角形、および画像属性を使用するクラス. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | の新しいインスタンスを初期化します`TextureBrush`指定された画像、外接する四角形、および画像属性を使用するクラス. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | の新しいインスタンスを初期化します`TextureBrush`指定された画像、ラップ モード、外接する四角形を使用するクラス. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | の新しいインスタンスを初期化します`TextureBrush`指定された画像、ラップ モード、外接する四角形を使用するクラス. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | を取得します[`Image`](../../aspose.psd/image/)これに関連付けられたオブジェクト`TextureBrush`object. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | を取得します[`ImageAttributes`](./imageattributes/)これに関連する`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | を取得します[`Rectangle`](../../aspose.psd/rectangle/)これに関連する`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 変換が何らかの方法で変更されたかどうかを示す値を取得します。たとえば、変換マトリックスを設定するか、変換マトリックスを変更するメソッドのいずれかを呼び出す 。このプロパティは、GDI+. との後方互換性のために導入されました。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。値 0 はブラシが完全に表示されることを意味し、値 1 はブラシが完全に不透明であることを意味します。 |
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

### 関連項目

* class [TransformBrush](../transformbrush/)
* 名前空間 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 組み立て [Aspose.PSD](../../)


