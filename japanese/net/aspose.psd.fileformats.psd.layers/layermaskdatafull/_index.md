---
title: Class LayerMaskDataFull
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull クラス. レイヤーにレイヤー マスクとベクター マスクの両方がある場合にPSD ファイル layer 内のマスク データに関する情報を含む LayerMaskDataFull クラスを定義しますそうでなければLayerMaskDataShort ImageData にはラスター マスクとラスター化されたベクトル マスクの組み合わせが含まれます
type: docs
weight: 2250
url: /ja/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

レイヤーにレイヤー マスクとベクター マスクの両方がある場合に、PSD ファイル layer 内のマスク データに関する情報を含む LayerMaskDataFull クラスを定義します。そうでなければ、[`LayerMaskDataShort`](../layermaskdatashort/) ImageData には、ラスター マスクとラスター化されたベクトル マスクの組み合わせが含まれます。

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | 背景色を取得または設定します。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 最下層のマスク位置を取得または設定します。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | レイヤーマスクマスクデータのサイズを取得します. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | デフォルトの色を取得または設定します。 |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | PSD イメージ レイヤー内の囲んでいる下部ラスター マスク位置を取得または設定します。 |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | PSD ファイル レイヤーで囲んでいる左のラスター マスク位置を取得または設定します。 |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | PSD ファイル レイヤー内の外側のラスター マスク位置を取得または設定します。 |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | PSD イメージ レイヤー内のラスター マスクを囲む上部位置を取得または設定します。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | レイヤー マスク フラグを取得または設定します。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD ファイル内のレイヤー マスク データ (または、ベクター マスクがある場合は結合/最終マスク) を取得または設定します。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 左レイヤー マスクの位置を取得または設定します。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | マスクを取得または設定します[`Rectangle`](../../aspose.psd/rectangle/)PSDファイルのレイヤーマスクの. 左、右、上、下のプロパティを取り、作成します[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | ユーザー/ラスター マスクに使用されるレイヤー マスク フラグを取得または設定します。ベクトル マスクの場合、Flags プロパティが使用されます。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 正しいレイヤー マスクの位置を取得または設定します。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 最上層のマスク位置を取得または設定します。 |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | PSD ファイル内のレイヤーのユーザー (ラスター) マスク データを取得または設定します。 (MaskData プロパティにレート化されたベクトル マスクがあります). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | PSD イメージ レイヤーのユーザー マスク (囲む) 四角形を取得または設定します.. |

### 関連項目

* class [LayerMaskData](../layermaskdata/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 組み立て [Aspose.PSD](../../)


