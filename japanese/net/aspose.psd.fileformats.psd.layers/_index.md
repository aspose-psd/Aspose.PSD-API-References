---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD for .NET API リファレンス
description: 名前空間には PSD ファイル形式のレイヤーが含まれています.
type: docs
weight: 210
url: /ja/net/aspose.psd.fileformats.psd.layers/
---
名前空間には PSD ファイル形式のレイヤーが含まれています.

## クラス

| クラス | 説明 |
| --- | --- |
| [BlendRange](./blendrange/) | ブレンド範囲. |
| [ChannelInformation](./channelinformation/) | チャンネル情報. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | グローバル レイヤー マスク セクション。 |
| [Layer](./layer/) | psd レイヤー。 |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | レイヤーのブレンド範囲データ. |
| [LayerGroup](./layergroup/) | グループ層 class |
| [LayerHashCalculator](./layerhashcalculator/) | PSD レイヤーのハッシュ計算機。異なるPSDファイルで等しいレイヤーまたは異なるレイヤーを見つけるために使用できます |
| [LayerMaskData](./layermaskdata/) | PSD ファイルのレイヤー マスク データに関する情報を含む基本 LayerMaskData クラスを定義します。 Adobe® Photoshop® ファイルをプログラムで変更し、PSD 形式の編集を自動化するのに役立ちます。 レイヤーにラスター マスクしかない場合、ImageData にはラスターが含まれます。 mask data bytes. レイヤーにベクター マスクしかない場合、ImageData にはベクター マスクのラスター化 (キャッシュ) されたデータ バイトが含まれます。の[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)バイト長は等しくなければなりません 幅 * 高さ[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/)properties. チャネルが更新されないため、LayerMaskData を削除/追加/更新するだけでは、適切な save には不十分であることに注意してください。ただし、正しいレンダリングが提供される場合があります. [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/)そのためにメソッドを使用する必要があります. |
| [LayerMaskDataFull](./layermaskdatafull/) | レイヤーにレイヤー マスクとベクター マスクの両方がある場合に、PSD ファイル layer 内のマスク データに関する情報を含む LayerMaskDataFull クラスを定義します。そうでなければ、[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) ImageData には、ラスター マスクとラスター化されたベクトル マスクの組み合わせが含まれます。 |
| [LayerMaskDataShort](./layermaskdatashort/) | レイヤーにラスター マスクまたはベクター マスクのみがあり、両方は含まれていない場合に、PSD ファイル layer 内のマスク データに関する情報を含む LayerMaskDataShort クラスを定義します。そうでなければ、[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) レイヤーにラスター マスクしかない場合、ImageData にはラスター マスク データ バイトが含まれます。[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)バイト長は等しくなければなりません 幅 * 高さ[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/)プロパティ. |
| [LayerResource](./layerresource/) | レイヤー情報を表します. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | PSD ファイルをロードするためのレイヤ リソース レジストリを定義します。 |
| [LinkedLayersManager](./linkedlayersmanager/) | リンクされたレイヤ マネージャ クラス. |
| [SectionDividerLayer](./sectiondividerlayer/) | フォルダーの境界をマークするセクション区切りレイヤー (レイヤー グループ). |
| [TextLayer](./textlayer/) | テキストレイヤー class |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | 塗りつぶし設定のベース インターフェイス |
| [ILayerResourceLoader](./ilayerresourceloader/) | レイヤ リソース ローダー。 |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [LayerFlags](./layerflags/) | レイヤーフラグ |
| [LayerMaskFlags](./layermaskflags/) | レイヤーマスク flags |


