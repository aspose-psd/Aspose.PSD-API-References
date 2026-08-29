---
title: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources"
second_title: "Aspose.PSD for .NET API Reference"
description: "この名前空間にはレイヤーに含まれる PSD ファイル形式エンティティが含まれています"
type: docs
weight: 300
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/
---
{{< psd/tize >}}
この名前空間にはレイヤーに含まれる PSD ファイル形式のエンティティが含まれています。

## クラス

| クラス | 説明 |
| --- | --- |
| [AbddResource](./abddresource/) | アートボード情報データ。 |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | 調整レイヤーリソースの基底クラス |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | アニメーションデータを含むセクションです。 |
| [ArtBResource](./artbresource/) | アートボード情報データ（[`Resources`](../aspose.psd.fileformats.psd.layers/layer/resources/) 用）。 |
| [ArtDResource](./artdresource/) | アートボード情報データ（[`GlobalLayerResources`](../aspose.psd.fileformats.psd/psdimage/globallayerresources/) 用）。 |
| [BaseArtboardInfoResource](./baseartboardinforesource/) | アートボード情報データリソースです。 |
| [BaseFxResource](./basefxresource/) | 基底エフェクトリソース |
| [BaseLayerSectionResource](./baselayersectionresource/) | レイヤーセクションリソースの基底クラス |
| [BlncResource](./blncresource/) | BlncResource クラスは Color Adjustment Layer のリソースです。 |
| [BlwhResource](./blwhresource/) | BlwhResource クラスは Black and White Adjustment Layer のリソースです。 |
| [BooleanResource](./booleanresource/) | BooleanResource クラス。これは疑似リソースです。Photoshop には存在しません |
| [BritResource](./britresource/) | BritResource クラス。Brightness/Contrast Adjustment Layer のリソースです。 |
| [CgEdResource](./cgedresource/) | CgEdResource クラス。Content Generator Extra Data（Photoshop CS5） |
| [ClassID](./classid/) | PSD クラス ID オブジェクトです。 |
| [ClblResource](./clblresource/) | ClblResource クラス。このリソースはクリップされた要素のブレンド情報を含みます。 |
| [CmlsResource](./cmlsresource/) | CmlsResource クラス。 |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) には HSV パラメータを変更できる 6 つのカラーレンジがあります。各レンジは範囲境界を識別するための 4 つのキー ポイントを持ちます。そしてそれは ColorRangeHsl です。 |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Curves Adjustment Layer のカーブを操作するマネージャー |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Curves Adjustment Layer のピクセルマップを操作するマネージャー |
| [CurvesManager](./curvesmanager/) | CurvResource を管理する基底クラス |
| [CurvResource](./curvresource/) | CurvResource クラス。Curves Adjustment Layer のリソースです。1 バイト - 曲線を使用する場合は 0、ピクセルマップを使用する場合は 1。0 の場合は: 2 バイト - short。デフォルトは 1。4 バイト - int。ビットで最後のバイトのみ使用されます。最初のビットは 1 チャンネル用、4 番目のビットは 4 チャンネル用です。例: 2 バイト - short、ポイント数。4 バイト * ポイント数 - カーブのポイント。2 short: 最初の位置、2 番目の高さ。4 バイト - word \"Crv \"。2 バイト - short、デフォルトは Curves の場合 4。4 バイト - int。デフォルトは 1。4 バイト - ポイント数。4 バイト * ポイント数 - カーブのポイント。2 short: 最初の位置、2 番目の高さ。0-4 バイト - 4 つの場合は折りたたみになる。1 の場合は: 2 バイト - short。デフォルトは 1。4 バイト - int。最後のバイトのみ使用されます。1 チャンネルは 1 ビットに、4 チャンネルは 4 ビットに割り当てられます。例: 256 * 変更されたチャンネル数 - 0 から 255 の範囲のチャンネル順序値。4 バイト - word \"Crv \"。2 バイト - short、デフォルトはピクセルマップの場合 3。4 バイト - int、チャンネル数 (2 + 256) バイト - short、2 はチャンネルインデックス、256 は 0 から 255 の範囲のチャンネル順序値です。 |
| [CustResource](./custresource/) | CustResource クラス。このリソースはクリップされた要素のブレンド情報を含みます。 |
| [ExpaResource](./exparesource/) | クラス ExpaResource。露光調整レイヤーのリソース |
| [FillLayerResource](./filllayerresource/) | 塗りレイヤーリソースの基底クラス。 |
| [FilterEffectMaskData](./filtereffectmaskdata/) | フィルターマスクデータクラス。 |
| [FXidResource](./fxidresource/) | フィルターエフェクトリソースには、チャンネル、ユーザーマスク、スマートフィルタ用のシートマスクが含まれます。 |
| [FxrpResource](./fxrpresource/) | クラス FxrpResource。レイヤーの参照ポイント。 |
| [GdFlResource](./gdflresource/) | クラス GdFlResource。このリソースは、クリップされた要素のブレンド情報を含みます。 |
| [GrdmResource](./grdmresource/) | クラス GrdmResource。グラデーションマップレイヤーに関する情報を含みます。 |
| [Hue2Resource](./hue2resource/) | クラス Hue2Resource。露光調整レイヤーのリソース。 |
| [IfxsResource](./ifxsresource/) | Ifxs リソース（グループレイヤーエフェクトリソース） |
| [ImfxResource](./imfxresource/) | Imfx リソース（マルチエフェクトリソース） |
| [InfxResource](./infxresource/) | クラス InfxResource。このリソースは、クリップされた要素のブレンド情報を含みます。 |
| [IopaResource](./ioparesource/) | クラス IopaResource。このリソースは、レイヤースタイルフォームからの塗り不透明度プロパティに関する情報を含みます。 |
| [KnkoResource](./knkoresource/) | クラス KnkoResource。このリソースは、クリップされた要素のブレンド情報を含みます。 |
| [LayerSectionResource](./layersectionresource/) | レイヤーセクションリソース。 |
| [LclrResource](./lclrresource/) | クラス LclrResource。このリソースは、PS のレイヤーリストにあるレイヤーの色に関する情報を含みます。これは唯一です。 |
| [LevelChannel](./levelchannel/) | レベル調整レイヤーのチャンネルを操作するためのクラス |
| [LevlResource](./levlresource/) | クラス LevlResource。露光調整レイヤーのリソース。 |
| [Lfx2Resource](./lfx2resource/) | Lfx2 リソース（レギュラーエフェクトリソース） |
| [LiFdDataSource](./lifddatasource/) | PSD ファイル内の埋め込みファイルに関する情報を含む liFD データソースクラスを定義します。これは、Adobe® Photoshop® ファイルの変更を支援する PSD ファイル形式操作 API の一部です。 |
| [LiFeDataSource](./lifedatasource/) | 外部リンクファイルに関する情報を含む LnkeDataSource クラスを定義します。これは、Adobe® Photoshop® ファイルの変更を支援する PSD ファイル形式操作 API の一部です。 |
| [LinkDataSource](./linkdatasource/) | PSD ファイル内のリンクファイルまたはアセットに関する情報を含む LinkDataSource クラスを定義します。 |
| [LinkResource](./linkresource/) | PSD 形式画像内のリンクまたは埋め込みファイルに関する情報を含む LinkResource クラスを定義します。リンクリソースは、インデクサでアクセスできる複数の [`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) インスタンスを含む場合があります。 |
| [LmskResource](./lmskresource/) | LMsk リソース。 |
| [Lnk2Resource](./lnk2resource/) | PSD 形式画像内の埋め込みファイルに関する情報を含むクラスを定義します。リンクリソースは、インデクサでアクセスできる複数の [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) インスタンスを含む場合があります。 |
| [Lnk3Resource](./lnk3resource/) | PSD 形式の 32 ビット/チャンネル画像内の埋め込みファイルに関する情報を含むクラスを定義します。リンクリソースは、インデクサでアクセスできる複数の [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) インスタンスを含む場合があります。 |
| [LnkeResource](./lnkeresource/) | LnkeResource クラスを定義します。このクラスは PSD 形式画像における外部リンクファイルまたはアセットに関する情報を含みます。リンクリソースはインデクサでアクセス可能な複数の [`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) インスタンスを含む場合があります。これは Adobe® Photoshop® ファイルをプログラムで変更するのに役立つ PSD ファイル形式操作 API の一部です。 |
| [LnsrResource](./lnsrresource/) | lnsrResource クラス。 |
| [Lr16Resource](./lr16resource/) | lr16 リソース。 |
| [Lr32Resource](./lr32resource/) | lr32 リソース。 |
| [LrXxResource](./lrxxresource/) | lrXX リソース。 |
| [LsdkResource](./lsdkresource/) | lsdk レイヤーリソース（ネストされたレイヤーセクションリソース）。 |
| [LspfResource](./lspfresource/) | レイヤー保護設定 |
| [LuniResource](./luniresource/) | レイヤー名リソース |
| [LyidResource](./lyidresource/) | LyidResource クラス。 |
| [LyvrResource](./lyvrresource/) | レイヤーの Photoshop バージョンを表すリソース。 |
| [MixrResource](./mixrresource/) | MixrResource クラス。Channel Mixer 調整レイヤーのリソース |
| [MlstResource](./mlstresource/) | mlst リソース。このクラスはその他にもレイヤーのタイムライン上の位置に関する情報を含みます。 |
| [NvrtResource](./nvrtresource/) | NvrtResource クラス。Invert 調整レイヤーのリソース。 |
| [OSTypeStructure](./ostypestructure/) | OS タイプ構造を表します。 |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) リソースレジストリを表します。 |
| [PathShape](./pathshape/) | ベジェ曲線のノットからの図形。 |
| [PattResource](./pattresource/) | PattResource クラス。パターンデータを含むリソース |
| [PattResourceData](./pattresourcedata/) | [`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) リソースのパターンデータを保存するクラスです。 |
| [PhflResource](./phflresource/) | PhflResource クラス。Exposure 調整レイヤー 2 のリソース バージョン ( = 3 ) または ( = 2 ) 12 4 バイトずつ XYZ カラー（バージョン 3 のみ） 10 2 バイトのカラースペースに続く 4 * 2 バイトのカラ―コンポーネント（バージョン 2 のみ） 4 密度 1 輝度保持 |
| [PhflResourceVersion2](./phflresourceversion2/) | PhflResource クラス。Exposure 調整レイヤー 2 のリソース バージョン ( = 3 ) または ( = 2 ) 12 4 バイトずつ XYZ カラー（バージョン 3 のみ） 10 2 バイトのカラースペースに続く 4 * 2 バイトのカラ―コンポーネント（バージョン 2 のみ） 4 密度 1 輝度保持 |
| [PhflResourceVersion3](./phflresourceversion3/) | PhflResource クラス。Exposure 調整レイヤー 2 のリソース バージョン ( = 3 ) または ( = 2 ) 12 4 バイトずつ XYZ カラー（バージョン 3 のみ） 10 2 バイトのカラースペースに続く 4 * 2 バイトのカラ―コンポーネント（バージョン 2 のみ） 4 密度 1 輝度保持 |
| [PlacedResource](./placedresource/) | PlacedResource クラスを定義します。このクラスは PSD ファイル内の配置レイヤーまたはスマートオブジェクトレイヤーに関する共通情報を含みます。Adobe® Photoshop® 画像におけるスマートオブジェクトレイヤーのサポートに使用されます。 |
| [PlLdResource](./plldresource/) | PlLdResource クラスを定義します。このクラスは PSD ファイル内の配置レイヤーに関する情報を含みます。Adobe® Photoshop® 画像におけるスマートオブジェクトレイヤーのサポートに使用されます。Adobe® Photoshop® CS3 では SoLdResource に置き換えられました。 |
| [PostResource](./postresource/) | PostResource クラス。ポスタライズレイヤー設定。 |
| [PtFlResource](./ptflresource/) | PtFlResource クラス。パターンフィルレイヤーデータを含みます。 |
| [ShmdResource](./shmdresource/) | ShmdResource クラス。メタデータ設定 |
| [SmartObjectResource](./smartobjectresource/) | SmartObjectResource クラスを定義します。このクラスは PSD ファイル内のスマートオブジェクトレイヤーに関する情報を含みます。Adobe® Photoshop® 画像におけるスマートオブジェクトレイヤーのサポートに使用される Sold および Sole リソースの基底クラスです。 |
| [SmartResourceCreator](./smartresourcecreator/) | SmartResourceCreator クラスを定義し、PlLd、SoLd、SoLe リソースを作成できます。Adobe® Photoshop® 画像でスマートオブジェクトレイヤーをサポートするために使用されます。 |
| [SoCoResource](./socoresource/) | SoCoResource クラス。このリソースは Color Fill Layers に関する情報を含みます。 |
| [SoLdResource](./soldresource/) | SoLdResource クラスを定義し、PSD ファイル内のスマートオブジェクトレイヤーに関する情報を含みます。Adobe� Photoshop� 画像でスマートオブジェクトレイヤーをサポートするために使用されます。 |
| [SoLeResource](./soleresource/) | SoLeResource クラスを定義し、PSD ファイル内のスマートオブジェクトレイヤーに関する情報を含みます。外部ファイルリンクを伴うスマートオブジェクトレイヤーを Adobe� Photoshop� 画像でサポートするために使用されます。 |
| [Txt2Resource](./txt2resource/) | Txt2 リソースクラス |
| [TypeToolFontInfo](./typetoolfontinfo/) | タイプツールのフォントに関する情報を含みます。 |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | タイプツール情報。PSD バージョン 6.0 以上の場合。 |
| [TypeToolInfoResource](./typetoolinforesource/) | タイプツール情報。PSD バージョン 6.0 未満の場合。 |
| [TypeToolLineInfo](./typetoollineinfo/) | タイプツールのライン情報。 |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | タイプツールのスタイル情報。 |
| [UnknownResource](./unknownresource/) | 不明なリソースです。 |
| [VectorPath](./vectorpath/) | ベクトルパスを含むクラスです。 |
| [VectorPathDataResource](./vectorpathdataresource/) | VectorPathDataResource クラス。このリソースはベクトルレイヤーマスクに関する情報を含みます。 |
| [VibAResource](./vibaresource/) | VibA リソース。 |
| [VmskResource](./vmskresource/) | VmskResource クラス。このリソースはベクトルレイヤーマスクに関する情報を含みます。 |
| [VogkResource](./vogkresource/) | Vector Origination Data リソースです。 |
| [VsmsResource](./vsmsresource/) | VsmsResource クラス。このリソースはベクトルレイヤーマスクに関する情報を含みます。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | この [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) リソースローダーです。 |
| [IPath](./ipath/) | インターフェイスは Shape レイヤーに存在するパスの集合を記述します。 |
| [IPathShape](./ipathshape/) | ベジェ曲線のノットからなるシェイプです。 |
| [IPlacedLayerResource](./iplacedlayerresource/) | IPlacedLayerResource インターフェイスを定義し、PSD ファイル内の配置レイヤーに関する情報を含みます。Adobe® Photoshop® 画像で PlLd、Sold、Sole リソースを指定するために使用されるマークアップインターフェイスです。Adobe® Photoshop® 画像でスマートオブジェクトレイヤーをサポートするために使用されます。 |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | ISmartObjectLayerResource インターフェイスを定義し、PSD ファイル内のスマートオブジェクトレイヤーリソースに関する情報を含みます。Adobe® Photoshop® 画像で Sold と Sole の両方のリソースを指定するために使用されるマークアップインターフェイスでもあります。 |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [LayerLockType](./layerlocktype/) | レイヤーロックオプション |
| [LayerSectionSubtype](./layersectionsubtype/) | セクションサブタイプ |
| [LayerSectionType](./layersectiontype/) | レイヤーセクションタイプ |
| [LinkDataSourceType](./linkdatasourcetype/) | PSDリンクリソースのデータソース用に LinkDataSourceType 列挙体を定義します。 |
| [LnsrResourceType](./lnsrresourcetype/) | 可能な Lnsr リソースタイプを検出しました |
| [PlacedLayerType](./placedlayertype/) | 配置レイヤー PlLd リソース用に PlacedLayerType 列挙体を定義します。 |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | シートカラー設定の可能な色です。PS のレイヤーリスト内のレイヤーの UI 装飾色です。 |


