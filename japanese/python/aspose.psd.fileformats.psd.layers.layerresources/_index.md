---
title: "aspose.psd.fileformats.psd.layers.layerresources"
type: docs
weight: 330
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/
---




## **Classes**
| **Class** | **説明** |
| :- | :- |
| [AbddResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/) | アートボード情報データです。 |
| [AdjustmentLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/) | 調整レイヤーリソースの基底クラス |
| [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | アニメーションデータを含むセクションです。 |
| [ArtBResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) | アートボード情報データは [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 用です。 |
| [ArtDResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/) | アートボード情報データは [PsdImage.global_layer_resources](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 用です。 |
| [BaseArtboardInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/) | アートボード情報データリソースです。 |
| [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) | BlncResource クラスは Color Adjustment Layer のリソースです。 |
| [BlwhResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/) | BlwhResource クラスは Black and White Adjustment Layer のリソースです。 |
| [BooleanResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/booleanresource/) | BooleanResource クラス。これは疑似リソースです。Photoshop にはありません。 |
| [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) | BritResource クラス。Brightness/Contrast Adjustment Layer のリソースです。 |
| [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) | CgEdResource クラス。Content Generator Extra Data (Photoshop CS5) |
| [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid/) | PSD クラス ID オブジェクトです。 |
| [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) | ClblResource クラス。<br/>            このリソースはクリップされた要素のブレンド情報を含みます。 |
| [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) | CmlsResource クラスです。 |
| [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) | [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) には HSV パラメータを変更できる 6 つのカラーレンジがあります。<br/>            各レンジは範囲の境界を識別するための 4 つのキーポイントを持ちます。そしてそれは ColorRangeHsl です。 |
| [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) | CurvResource クラス。Curves Adjustment Layer のリソース<br/>            1 バイト - カーブを使用する場合は 0、マップ上のピクセルを使用する場合は 1<br/>            0 の場合:<br/>            2 バイト - short。デフォルトは 1<br/>            4 バイト - int。ビットで最後のバイトのみ使用。最初のビットは 1 チャンネル用、4 番目のビットは例として 4 チャンネル用<br/>            2 バイト - short ポイント数<br/>            4 バイト * ポイント数 - カーブのポイント 2 short: 最初の位置、2 番目の高さ<br/>            4 バイト - ワード \"Crv \"<br/>            2 バイト - short デフォルトは Curves 用に 4<br/>            4 バイト - int。デフォルトは 1<br/>            4 バイト - ポイント数<br/>            4 バイト * ポイント数 - カーブのポイント 2 short: 最初の位置、2 番目の高さ<br/>            0-4 バイト - 四つのフォールド用リーディング<br/>            1 の場合:<br/>            2 バイト - short。デフォルトは 1<br/>            4 バイト - int。最後のバイトのみ使用。1 チャンネルは 1 ビットに、例として 4 チャンネルは 4 ビットに<br/>            256 * 変更されたチャンネル数 - 0〜255 の範囲のチャンネル順序値<br/>            4 バイト - ワード \"Crv \"<br/>            2 バイト - short。マップ上のピクセル用デフォルトは 3<br/>            4 バイト - int チャンネル数<br/>            (2 + 256) バイト - short 2 はチャンネルインデックス、256 は 0〜255 の範囲のチャンネル順序値 |
| [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) | カーブを操作する Curves Adjustment Layer のマネージャー |
| [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) | ピクセルマップを操作するカーブ調整レイヤーのマネージャー |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | CurvResource を管理するための基底クラス |
| [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) | クラス CustResource.<br/>            このリソースはクリップされた要素のブレンドに関する情報を含みます。 |
| [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) | クラス ExpaResource。露光調整レイヤーのリソース |
| [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) | フィルターエフェクトリソースは、チャンネル、ユーザーマスク、およびスマートフィルタ用のシートマスクを含みます。 |
| [FillLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filllayerresource/) | 塗りレイヤーリソース用の基底クラス。 |
| [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) | フィルターマスクデータクラスです。 |
| [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) | クラス FxrpResource。レイヤーの参照点 |
| [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) | クラス GdFlResource.<br/>            このリソースはクリップされた要素のブレンドに関する情報を含みます。 |
| [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) | クラス GrdmResource。グラデーションマップレイヤーに関する情報を含みます。 |
| [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) | クラス Hue2Resource。露光調整レイヤーのリソース |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/) | この [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) リソースローダーです。 |
| [IPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipath/) | インターフェースは、シェイプレイヤーに存在するパスの集合を記述します。 |
| [IPathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/) | ベジェ曲線のノットからなるシェイプです。 |
| [IPlacedLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/) | PSD ファイル内の配置レイヤーに関する情報を含む IPlacedLayerResource インターフェースを定義します。<br/>            これは Adobe® Photoshop® 画像内の PlLd、Sold、Sole リソースを指定するために使用されるマークアップインターフェースです。<br/>            これは Adobe® Photoshop® 画像内のスマートオブジェクトレイヤーをサポートするために使用されます。 |
| [ISmartObjectLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/) | PSD ファイル内のスマートオブジェクトレイヤーリソースに関する情報を含む ISmartObjectLayerResource インターフェースを定義します。<br/>            これは Adobe® Photoshop® 画像内の Sold と Sole の両方のリソースを指定するために使用されるマークアップインターフェースでもあります。 |
| [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) | クラス InfxResource.<br/>            このリソースはクリップされた要素のブレンドに関する情報を含みます。 |
| [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) | クラス IopaResource.<br/>            このリソースはレイヤースタイルフォームからの塗り不透明度プロパティに関する情報を含みます。 |
| [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) | クラス KnkoResource.<br/>            このリソースはクリップされた要素のブレンドに関する情報を含みます。 |
| [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) | レイヤーセクションリソースです。 |
| [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) | クラス LclrResource.<br/>            このリソースは、PS のレイヤーリスト内のレイヤーの色に関する情報を含みます。これは唯一です。 |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel/) | レベル調整レイヤーのチャンネルを操作するためのクラス |
| [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) | クラス LevlResource。露光調整レイヤーのリソース |
| [Lfx2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/) | Lfx2 リソース（エフェクトリソース） |
| [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) | 埋め込みファイルに関する情報を含む PSD ファイル内の liFD データソースクラスを定義します。<br/>            これは Adobe® Photoshop® ファイルの変更を支援する PSD ファイルフォーマット操作 API の一部です。 |
| [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) | 外部リンクファイルに関する情報を含む LnkeDataSource クラスを定義します。<br/>            これは Adobe® Photoshop® ファイルの変更を支援する PSD ファイル形式操作 API の一部です |
| [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | PSD ファイル内のリンクされたファイルまたはアセットに関する情報を含む LinkDataSource クラスを定義します。 |
| [LinkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/) | PSD 形式画像内のリンクまたは埋め込みファイルに関する情報を含む LinkResource クラスを定義します。<br/>            このリンクリソースは、派生クラスのインデクサでアクセス可能な複数の [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) インスタンスを含む場合があります。 |
| [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) | LMsk リソースです。 |
| [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) | PSD 形式画像内の埋め込みファイルに関する情報を含むクラスを定義します。<br/>            このリンクリソースは、インデクサでアクセス可能な複数の [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) インスタンスを含む場合があります。 |
| [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) | PSD 形式の 32 ビット/チャンネル画像における埋め込みファイルに関する情報を含むクラスを定義します。<br/>            このリンクリソースは、インデクサでアクセス可能な複数の [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) インスタンスを含む場合があります。 |
| [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) | PSD 形式画像内の外部リンクファイルまたはアセットに関する情報を含む LnkeResource クラスを定義します。<br/>            このリンクリソースは、インデクサでアクセス可能な複数の [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) インスタンスを含む場合があります。<br/>            これは Adobe® Photoshop® ファイルをプログラムで変更するのに役立つ PSD ファイル形式操作 API の一部です |
| [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) | lnsrResource クラスです。 |
| [Lr16Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/) | lr16 リソースです。 |
| [Lr32Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/) | lr32 リソースです。 |
| [LrXxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/) | lrXX リソースです。 |
| [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) | レイヤー保護設定 |
| [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) | レイヤー名リソース |
| [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) | LyidResource クラスです。 |
| [LyvrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/) | レイヤーの Photoshop バージョンを表すリソースです。 |
| [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) | MixrResource クラス。チャンネルミキサー調整レイヤーのリソースです |
| [MlstResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/) | mlst リソースです。<br/>            このクラスは、その他にもレイヤーのタイムライン上の位置に関する情報を含みます。 |
| [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) | NvrtResource クラス。インバート調整レイヤーのリソースです。 |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) | OS タイプ構造体を表します。 |
| [OSTypeStructuresRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/) | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) リソースレジストリを表します。 |
| [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) | ベジェ曲線のノットから得られる図形です。 |
| [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) | PattResource クラス。パターンデータを含むリソースです |
| [PattResourceData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/) | [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) リソースのパターンデータを保存するクラスです。 |
| [PhflResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/) | PhflResource クラス。露出調整レイヤーのリソースです<br/>            バージョン 2 ( = 3 ) または ( = 2 )<br/>            バージョン 3 のみ: XYZ カラーごとに 4 バイトずつ、合計 12 バイト<br/>            バージョン 2 のみ: カラースペース 2 バイトに続き、4 * 2 バイトのカラ―コンポーネント、合計 10 バイト<br/>            密度 4<br/>            輝度保持 1 |
| [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) | PhflResource クラス。露出調整レイヤーのリソースです<br/>            バージョン 2 ( = 3 ) または ( = 2 )<br/>            バージョン 3 のみ: XYZ カラーごとに 4 バイトずつ、合計 12 バイト<br/>            バージョン 2 のみ: カラースペース 2 バイトに続き、4 * 2 バイトのカラ―コンポーネント、合計 10 バイト<br/>            密度 4<br/>            輝度保持 1 |
| [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) | PhflResource クラス。露出調整レイヤーのリソースです<br/>            バージョン 2 ( = 3 ) または ( = 2 )<br/>            バージョン 3 のみ: XYZ カラーごとに 4 バイトずつ、合計 12 バイト<br/>            バージョン 2 のみ: カラースペース 2 バイトに続き、4 * 2 バイトのカラ―コンポーネント、合計 10 バイト<br/>            密度 4<br/>            輝度保持 1 |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) | PSD ファイル内の配置レイヤーに関する情報を含む PlLdResource クラスを定義します。<br/>            これは Adobe� Photoshop� 画像のスマートオブジェクトレイヤーをサポートするために使用されます。<br/>            Adobe� Photoshop� CS3 では SoLdResource に置き換えられました |
| [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/) | PSD ファイル内の配置レイヤまたはスマートオブジェクトレイヤに関する共通情報を含む PlacedResource クラスを定義します。<br/>            Adobe� Photoshop� 画像でスマートオブジェクトレイヤをサポートするために使用されます。 |
| [PostResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/) | クラス PostResource. ポスタライズレイヤ設定。 |
| [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) | クラス PtFlResource. パターン塗りつぶしレイヤデータを含みます。 |
| [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) | クラス ShmdResource. メタデータ設定 |
| [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) | PSD ファイル内のスマートオブジェクトレイヤに関する情報を含む SmartObjectResource クラスを定義します。<br/>            Sold と Sole リソースの基底クラスであり、Adobe� Photoshop� 画像でスマートオブジェクトレイヤをサポートするために使用されます。 |
| [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) | PlLd、SoLd、SoLe リソースを作成できる SmartResourceCreator クラスを定義します。<br/>            Adobe® Photoshop® 画像でスマートオブジェクトレイヤをサポートするために使用されます。 |
| [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) | クラス SoCoResource.<br/>            このリソースはカラー塗りつぶしレイヤに関する情報を含みます |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) | PSD ファイル内のスマートオブジェクトレイヤに関する情報を含む SoLdResource クラスを定義します。<br/>            Adobe� Photoshop� 画像でスマートオブジェクトレイヤをサポートするために使用されます。 |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) | PSD ファイル内のスマートオブジェクトレイヤに関する情報を含む SoLeResource クラスを定義します。<br/>            外部ファイルリンクを伴うスマートオブジェクトレイヤを Adobe� Photoshop� 画像でサポートするために使用されます。 |
| [Txt2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/) | Txt2 リソースクラス |
| [TypeToolFontInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo/) | タイプツールのフォントに関する情報を含みます。 |
| [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) | タイプツール情報。PSD バージョン 6.0 以上の場合。 |
| [TypeToolInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/) | タイプツール情報。PSD バージョン 6.0 未満の場合。 |
| [TypeToolLineInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo/) | タイプツールのライン情報。 |
| [TypeToolStyleInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo/) | タイプツールのスタイル情報。 |
| [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) | 不明なリソースです。 |
| [VectorPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/) | ベクトルパスを含むクラスです。 |
| [VectorPathDataResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/) | クラス VectorPathDataResource.<br/>            このリソースはベクトルレイヤマスクに関する情報を含みます |
| [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) | VibA リソース。 |
| [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) | クラス VmskResource.<br/>            このリソースはベクトルレイヤマスクに関する情報を含みます |
| [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) | ベクトル起源データリソースです。 |
| [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) | クラス VsmsResource.<br/>            このリソースはベクトルレイヤマスクに関する情報を含みます |
## **Enumerations**
| **列挙** | **説明** |
| :- | :- |
| [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | レイヤーロックオプション |
| [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype/) | セクションサブタイプ |
| [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype/) | レイヤーセクションタイプ |
| [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype/) | PSDリンクリソースのデータソース用に LinkDataSourceType 列挙体を定義します。 |
| [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype/) | 可能な Lnsr リソースタイプを検出しました。 |
| [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype/) | 配置レイヤー PlLd リソース用に PlacedLayerType 列挙体を定義します。 |
| [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | シートカラー設定の可能な色。<br/>            これは PS のレイヤーリスト内のレイヤーの UI 装飾色です。 |
