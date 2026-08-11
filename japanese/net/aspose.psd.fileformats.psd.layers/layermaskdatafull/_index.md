---
title: "クラス LayerMaskDataFull"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull クラス。レイヤーにレイヤーマスクとベクターマスクの両方がある場合の PSD ファイルレイヤー内のマスクデータに関する情報を含む LayerMaskDataFull クラスを定義します。それ以外の場合は LayerMaskDataShort が使用されます。ImageData はラスターマスクとラスタライズされたベクターマスクを結合したものを含みます。ImageData のバイト長は MaskRectangle.Width と MaskRectangle.Height のプロパティに等しい必要があります。"
type: docs
weight: 2450
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

レイヤーにレイヤーマスクとベクターマスクの両方がある場合の PSD ファイルレイヤー内のマスクデータに関する情報を含む LayerMaskDataFull クラスを定義します。それ以外の場合は [`LayerMaskDataShort`](../layermaskdatashort/) が使用されます。ImageData はラスターマスクとラスタライズされたベクターマスクを結合したものを含みます。ImageData のバイト長は MaskRectangle.Width * MaskRectangle.Height のプロパティに等しい必要があります。

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | 背景色を取得または設定します。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 下部レイヤーマスクの位置を取得または設定します。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | レイヤーマスクデータのサイズを取得します。 |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | デフォルトの色を取得または設定します。 |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | PSD 画像レイヤー内の下部ラスターマスクの位置を取得または設定します。 |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | PSD ファイルレイヤー内の左側ラスターマスクの位置を取得または設定します。 |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | PSD ファイルレイヤー内の右側ラスターマスクの位置を取得または設定します。 |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | PSD 画像レイヤー内のラスターマスクの上部位置を取得または設定します。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | レイヤーマスクのフラグを取得または設定します。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD ファイル内のレイヤーマスクデータ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 左側レイヤーマスクの位置を取得または設定します。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | PSD ファイル内のレイヤーマスクのマスク [`Rectangle`](../../aspose.psd/rectangle/) を取得または設定します。左、右、上、下のプロパティを受け取り、[`Rectangle`](../../aspose.psd/rectangle/) を作成します。 |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | ユーザー/ラスターマスクに使用されるレイヤーマスクのフラグを取得または設定します。ベクターマスクの場合は Flags プロパティが使用されます。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 右側レイヤーマスクの位置を取得または設定します。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 上部レイヤーマスクの位置を取得または設定します。 |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | PSD ファイル内のレイヤーのユーザー（ラスタ）マスクデータを取得または設定します。（MaskData プロパティにラスタライズされたベクターマスクがあります） |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | PSD 画像レイヤー内のユーザーマスク（囲み）矩形を取得または設定します。 |

### 関連項目

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


