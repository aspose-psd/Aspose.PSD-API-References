---
title: Class LayerMaskData
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData クラス. PSD ファイルのレイヤー マスク データに関する情報を含む基本 LayerMaskData クラスを定義します Adobe Photoshop ファイルをプログラムで変更しPSD 形式の編集を自動化するのに役立ちます レイヤーにラスター マスクしかない場合ImageData にはラスターが含まれます mask data bytes. レイヤーにベクター マスクしかない場合ImageData にはベクター マスクのラスター化 キャッシュ されたデータ バイトが含まれますのImageDataバイト長は等しくなければなりません 幅  高さMaskRectangleproperties. チャネルが更新されないためLayerMaskData を削除/追加/更新するだけでは適切な save には不十分であることに注意してくださいただし正しいレンダリングが提供される場合があります. AddLayerMaskそのためにメソッドを使用する必要があります.
type: docs
weight: 2240
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

PSD ファイルのレイヤー マスク データに関する情報を含む基本 LayerMaskData クラスを定義します。 Adobe® Photoshop® ファイルをプログラムで変更し、PSD 形式の編集を自動化するのに役立ちます。 レイヤーにラスター マスクしかない場合、ImageData にはラスターが含まれます。 mask data bytes. レイヤーにベクター マスクしかない場合、ImageData にはベクター マスクのラスター化 (キャッシュ) されたデータ バイトが含まれます。の[`ImageData`](./imagedata/)バイト長は等しくなければなりません 幅 * 高さ[`MaskRectangle`](./maskrectangle/)properties. チャネルが更新されないため、LayerMaskData を削除/追加/更新するだけでは、適切な save には不十分であることに注意してください。ただし、正しいレンダリングが提供される場合があります. [`AddLayerMask`](../layer/addlayermask/)そのためにメソッドを使用する必要があります.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 正しいレイヤー マスクの位置を取得または設定します。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 最上層のマスク位置を取得または設定します。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 組み立て [Aspose.PSD](../../)


