---
title: "クラス LayerMaskData"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData クラス。PSD ファイル内のレイヤーマスクデータに関する情報を含む基本的な LayerMaskData クラスを定義します。これにより、Adobe Photoshop ファイルをプログラムで変更したり、PSD 形式の編集を自動化したりできます。レイヤーにラスターマスクのみがある場合、ImageData はラスターマスクのデータバイトを含みます。ベクターマスクのみがある場合、ImageData はベクターマスクのラスタライズされたキャッシュデータバイトを含みます。レイヤーとベクターマスクの両方がある場合、ImageData はラスターマスクとラスタライズされたベクターマスクを結合したものを含みます。ImageData のバイト長は MaskRectangle プロパティの Width と Height に等しい必要があります。LayerMaskData を単に削除/追加/更新するだけでは、チャネルが更新されないため正しく保存できませんが、正しいレンダリングは提供できる場合があります。そのためには AddLayerMask メソッドを使用すべきです。"
type: docs
weight: 2440
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

基本的な LayerMaskData クラスを定義し、PSD ファイル内のレイヤーマスクデータに関する情報を含みます。これにより、Adobe® Photoshop® ファイルをプログラムで変更したり、PSD 形式の編集を自動化したりできます。レイヤーにラスターマスクのみがある場合、ImageData はラスターマスクのデータバイトを含みます。ベクターマスクのみがある場合、ImageData はベクターマスクのラスタライズされた（キャッシュされた）データバイトを含みます。レイヤーとベクターマスクの両方がある場合、ImageData はラスターマスクとラスタライズされたベクターマスクを結合したものを含みます。[`ImageData`](./imagedata/) のバイト長は [`MaskRectangle`](./maskrectangle/) プロパティの Width * Height に等しい必要があります。LayerMaskData を単に削除/追加/更新するだけでは、チャネルが更新されないため正しく保存できませんが、正しいレンダリングは提供できる場合があります。そのためには [`AddLayerMask`](../layer/addlayermask/) メソッドを使用すべきです。

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 右側レイヤーマスクの位置を取得または設定します。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 上部レイヤーマスクの位置を取得または設定します。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


