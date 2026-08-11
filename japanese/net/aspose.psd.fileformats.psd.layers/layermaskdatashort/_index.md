---
title: "クラス LayerMaskDataShort"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort クラス。レイヤーがラスターマスクまたはベクターマスクのいずれかのみを持ち、両方は持たない場合の PSD ファイルレイヤー内のマスクデータに関する情報を含む LayerMaskDataShort クラスを定義します。それ以外の場合は LayerMaskDataFull が使用されます。レイヤーがラスターマスクのみを持つ場合、ImageData はラスターマスクのデータバイトを含みます。ベクターマスクのみを持つ場合、ImageData はベクターマスクのラスタライズされたキャッシュデータバイトを含みます。ImageData のバイト長は MaskRectangle プロパティの Width と Height に等しい必要があります。"
type: docs
weight: 2460
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

レイヤーがラスターマスクまたはベクターマスクのいずれかのみを持ち、両方は持たない場合の PSD ファイルレイヤー内のマスクデータに関する情報を含む LayerMaskDataShort クラスを定義します。それ以外の場合は [`LayerMaskDataFull`](../layermaskdatafull/) が使用されます。レイヤーがラスターマスクのみを持つ場合、ImageData はラスターマスクのデータバイトを含みます。ベクターマスクのみを持つ場合、ImageData はベクターマスクのラスタライズされた（キャッシュされた）データバイトを含みます。[`ImageData`](../layermaskdata/imagedata/) のバイト長は [`MaskRectangle`](../layermaskdata/maskrectangle/) の Width * Height に等しい必要があります。

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | `LayerMaskDataShort` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 下部レイヤーマスクの位置を取得または設定します。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | レイヤーマスクデータのサイズを取得します。 |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | デフォルトの色を取得または設定します。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | レイヤーマスクのフラグを取得または設定します。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD ファイル内のレイヤーマスクデータ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 左側レイヤーマスクの位置を取得または設定します。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | PSD ファイル内のレイヤーマスクのマスク [`Rectangle`](../../aspose.psd/rectangle/) を取得または設定します。左、右、上、下のプロパティを受け取り、[`Rectangle`](../../aspose.psd/rectangle/) を作成します。 |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | レイヤーマスクのパディングを取得または設定します。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 右側レイヤーマスクの位置を取得または設定します。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 上部レイヤーマスクの位置を取得または設定します。 |

### 関連項目

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


