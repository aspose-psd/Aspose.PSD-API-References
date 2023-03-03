---
title: Class LayerMaskDataShort
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort クラス. レイヤーにラスター マスクまたはベクター マスクのみがあり両方は含まれていない場合にPSD ファイル layer 内のマスク データに関する情報を含む LayerMaskDataShort クラスを定義しますそうでなければLayerMaskDataFull レイヤーにラスター マスクしかない場合ImageData にはラスター マスク データ バイトが含まれますImageDataバイト長は等しくなければなりません 幅  高さMaskRectangleプロパティ.
type: docs
weight: 2260
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

レイヤーにラスター マスクまたはベクター マスクのみがあり、両方は含まれていない場合に、PSD ファイル layer 内のマスク データに関する情報を含む LayerMaskDataShort クラスを定義します。そうでなければ、[`LayerMaskDataFull`](../layermaskdatafull/) レイヤーにラスター マスクしかない場合、ImageData にはラスター マスク データ バイトが含まれます。[`ImageData`](../layermaskdata/imagedata/)バイト長は等しくなければなりません 幅 * 高さ[`MaskRectangle`](../layermaskdata/maskrectangle/)プロパティ.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 最下層のマスク位置を取得または設定します。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | レイヤーマスクマスクデータのサイズを取得します. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | デフォルトの色を取得または設定します。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | レイヤー マスク フラグを取得または設定します。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD ファイル内のレイヤー マスク データ (または、ベクター マスクがある場合は結合/最終マスク) を取得または設定します。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 左レイヤー マスクの位置を取得または設定します。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | マスクを取得または設定します[`Rectangle`](../../aspose.psd/rectangle/)PSDファイルのレイヤーマスクの. 左、右、上、下のプロパティを取り、作成します[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | レイヤー マスクのパディングを取得または設定します。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 正しいレイヤー マスクの位置を取得または設定します。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 最上層のマスク位置を取得または設定します。 |

### 関連項目

* class [LayerMaskData](../layermaskdata/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 組み立て [Aspose.PSD](../../)


