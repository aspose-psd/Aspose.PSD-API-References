---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /ja/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Class** | **説明** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | アートボードレイヤークラスです。 |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | ブレンド範囲です。 |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | チャンネル情報です。 |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | グローバルレイヤーマスクセクションです。 |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | 塗りつぶし設定の基本インターフェース |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | レイヤー リソース ローダー。 |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Shape レイヤーのプロパティを説明します。 |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | psd レイヤー。 |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | レイヤー ブレンディング範囲データ。 |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | グループレイヤークラス |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | PSD レイヤー用ハッシュ計算機。異なる PSD ファイル間で同一または異なるレイヤーを見つけるために使用できます。 |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | PSD ファイル内のレイヤーマスクデータに関する情報を含む基底 LayerMaskData クラスを定義します。<br/>            プログラムから Adobe® Photoshop® ファイルを変更し、PSD 形式の編集を自動化するのに役立ちます。<br/>            レイヤーにラスターマスクのみがある場合、ImageData はラスターマスクデータバイトを含みます。<br/>            レイヤーにベクターマスクのみがある場合、ImageData はベクターマスクをラスタライズ（キャッシュ）したデータバイトを含みます。<br/>            レイヤーにレイヤーマスクとベクターマスクの両方がある場合、ImageData はラスターマスクとラスタライズされたベクターマスクを結合したものを含みます。<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) のバイト長は、[LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) プロパティの Width * Height と等しくなる必要があります。<br/>            LayerMaskData の削除／追加／更新だけでは正しい保存には不十分で、チャンネルが更新されないため、正しいレンダリングが提供される場合があります。<br/>            そのためには [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) メソッドを使用すべきです。 |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | LayerMaskDataFull クラスを定義します。このクラスは、レイヤーがレイヤーマスクとベクターマスクの両方を持つ PSD ファイルレイヤーのマスクデータに関する情報を含みます。<br/>            それ以外の場合は、[LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) が使用されます。<br/>            ImageData はラスターマスクとラスタライズされたベクターマスクを結合したものを含みます。<br/>            ImageData のバイト長は MaskRectangle.Width * MaskRectangle.Height プロパティと等しくなる必要があります。 |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | LayerMaskDataShort クラスを定義します。このクラスは、レイヤーがラスターマスクまたはベクターマスクのいずれかのみを持ち、両方を持たない PSD ファイルレイヤーのマスクデータに関する情報を含みます。そうでない場合は、[LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) が使用されます。<br/>            レイヤーがラスターマスクのみを持つ場合、ImageData はラスターマスクデータバイトを含みます。<br/>            レイヤーがベクターマスクのみを持つ場合、ImageData はベクターマスクをラスタライズ（キャッシュ）したデータバイトを含みます。<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) のバイト長は、[LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) プロパティの Width * Height と等しくなる必要があります。 |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | レイヤー情報を表します。 |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | PSD ファイルの読み込み用レイヤーリソースレジストリを定義します。 |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | リンクされたレイヤー管理クラス。 |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | フォルダー（レイヤー グループ）の境界を示すセクション区切りレイヤー。 |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Shape レイヤー。Shape レイヤーと関連リソースの処理ロジックをカプセル化します。 |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | テキストレイヤークラス |
## **Enumerations**
| **列挙** | **説明** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | レイヤーフラグ |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | レイヤーマスクフラグ |
