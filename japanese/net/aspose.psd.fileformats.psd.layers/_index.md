---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD for .NET API Reference"
description: "この名前空間には PSD ファイル形式のレイヤーが含まれています"
type: docs
weight: 230
url: /ja/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
この名前空間には PSD ファイル形式のレイヤーが含まれています。

## クラス

| クラス | 説明 |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | アートボードレイヤークラスです。 |
| [BlendRange](./blendrange/) | ブレンド範囲です。 |
| [ChannelInformation](./channelinformation/) | チャンネル情報です。 |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | グローバルレイヤーマスクセクションです。 |
| [Layer](./layer/) | PSDレイヤーです。 |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | レイヤーのブレンド範囲データです。 |
| [LayerGroup](./layergroup/) | グループレイヤークラス |
| [LayerHashCalculator](./layerhashcalculator/) | PSDレイヤー用ハッシュ計算機です。異なるPSDファイル間で同一または異なるレイヤーを見つけるために使用できます。 |
| [LayerMaskData](./layermaskdata/) | PSDファイル内のレイヤーマスクデータに関する情報を含む基底 LayerMaskData クラスを定義します。これにより、Adobe® Photoshop® ファイルをプログラムで変更したり、PSD形式の編集を自動化したりできます。レイヤーがラスターマスクのみを持つ場合、ImageData はラスターマスクデータバイトを含みます。レイヤーがベクターマスクのみを持つ場合、ImageData はベクターマスクをラスタライズ（キャッシュ）したデータバイトを含みます。レイヤーがレイヤーマスクとベクターマスクの両方を持つ場合、ImageData はラスターマスクとラスタライズされたベクターマスクを組み合わせたものを含みます。[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) のバイト長は、[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) の Width * Height と等しくなる必要があります。LayerMaskData の削除/追加/更新だけではチャンネルが更新されないため、正しい保存には不十分であることに注意してください。ただし、正しいレンダリングは提供できる場合があります。そのためには [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) メソッドを使用すべきです。 |
| [LayerMaskDataFull](./layermaskdatafull/) | レイヤーがレイヤーマスクとベクターマスクの両方を持つ場合のPSDファイルレイヤーのマスクデータ情報を含む LayerMaskDataFull クラスを定義します。それ以外の場合は [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) が使用されます。ImageData はラスターマスクとラスタライズされたベクターマスクを組み合わせたものを含みます。ImageData のバイト長は MaskRectangle.Width * MaskRectangle.Height のプロパティと等しくなる必要があります。 |
| [LayerMaskDataShort](./layermaskdatashort/) | レイヤーがラスターマスクまたはベクターマスクのいずれか一方のみを持ち、両方を持たない場合のPSDファイルレイヤーのマスクデータ情報を含む LayerMaskDataShort クラスを定義します。それ以外の場合は [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) が使用されます。レイヤーがラスターマスクのみを持つ場合、ImageData はラスターマスクデータバイトを含みます。レイヤーがベクターマスクのみを持つ場合、ImageData はベクターマスクをラスタライズ（キャッシュ）したデータバイトを含みます。[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) のバイト長は、[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) の Width * Height と等しくなる必要があります。 |
| [LayerResource](./layerresource/) | レイヤー情報を表します。 |
| [LayerResourcesRegistry](./layerresourcesregistry/) | PSDファイルの読み込み用レイヤーリソースレジストリを定義します。 |
| [LinkedLayersManager](./linkedlayersmanager/) | リンクされたレイヤー管理クラスです。 |
| [SectionDividerLayer](./sectiondividerlayer/) | フォルダー（レイヤーグループ）の境界を示すセクション区切りレイヤーです。 |
| [ShapeLayer](./shapelayer/) | シェイプレイヤー。シェイプレイヤーと関連リソースの処理ロジックをカプセル化します。 |
| [TextLayer](./textlayer/) | テキストレイヤークラスです。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | 塗り設定の基本インターフェイス |
| [ILayerResourceLoader](./ilayerresourceloader/) | レイヤーリソースローダーです。 |
| [IShapeLayer](./ishapelayer/) | シェイプレイヤーのプロパティを説明します。 |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [LayerFlags](./layerflags/) | レイヤーフラグです。 |
| [LayerMaskFlags](./layermaskflags/) | レイヤーマスクフラグです。 |


