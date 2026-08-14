---
title: "aspose.psd"
type: docs
weight: 10
url: /ja/python-net/aspose.psd/
---


このモジュールは、入れ子モジュールのコアであり、Aspose.PSD の処理に使用される最も基本的なオブジェクトです。

## **Classes**
| **Class** | **説明** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | ブレンドパターンを定義します。このクラスは継承できません。 |
| [Brush](/psd/python-net/aspose.psd/brush/) | 基底ブラシクラスです。 |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | 現在のビルドバージョン情報を含みます。 |
| [Cache](/psd/python-net/aspose.psd/cache/) | キャッシュ設定を含みます。 |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | ピクセルのCMYKカラーです。 |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | 符号付き32ビット整数値として表現されたCMYKカラーを扱うためのヘルパーメソッドです。<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 構造体と同様の API を提供します。<br/>            CMYKカラーが内部フィールドを持つ構造体ではなく、Int32 として表現されるため、より軽量です。<br/>            可能な限り、非推奨となった<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 構造体の代わりに、このクラスの静的メソッドを使用してください。 |
| [Color](/psd/python-net/aspose.psd/color/) | ピクセルの色です。 |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | マルチカラーグラデーションで色のブレンドを補間するために使用される色と位置の配列を定義します。このクラスは継承できません。 |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | 色変換用のマップを定義します。[ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) クラスのいくつかのメソッドは、[ColorMap](/psd/python-net/aspose.psd/colormap/) 構造体の配列であるカラーリマップテーブルを使用して画像の色を調整します。継承できません。 |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | RGBA 空間の座標を含む 5 x 5 行列を定義します。[ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) クラスのいくつかのメソッドは、カラー行列を使用して画像の色を調整します。このクラスは継承できません。 |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | カラーパレットを構成する色の配列を定義します。これらの色は 32 ビット ARGB カラーです。継承できません。 |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | カラーパレット操作のためのヘルパークラスです。 |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | GDI+ Color 構造体との間で色を変換します。このクラスは継承できません。 |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | カスタムのユーザー定義ラインキャップをカプセル化します。 |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | データストリームコンテナです。 |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | 破棄可能なオブジェクトを表します。 |
| [Figure](/psd/python-net/aspose.psd/figure/) | 図形です。シェイプのコンテナです。 |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | ファイルストリーム処理のヘルパーです。 |
| [Font](/psd/python-net/aspose.psd/font/) | フォントファミリー、サイズ、スタイル属性を含むテキストの特定のフォーマットを定義します。このクラスは継承できません。 |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | 一般的な PSD ベクターフォーマットレンダラのフォント設定です。 |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | 現在のアセンブリで使用されているグラフィックエンジンに従ってグラフィックを表します。 |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | 連続した直線と曲線の系列を表します。このクラスは継承できません。 |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | 高度なバッファプロセッサです。 |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | バッファプロセッサです。 |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | カラーコンバータです。 |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | カラーパレットインターフェイスです。 |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | 画像クリエイターです。 |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | 画像クリエイターディスクリプタはクリエイターのプロパティを指定します。クリエイターディスクリプタは、<br/>            各画像クリエイターインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。 |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | 画像ディスクリプタ。すべての他の画像ディスクリプタタイプの基本プロパティとメソッドを含みます。 |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | 画像エクスポーター。内部の Aspose.PSD フォーマットから指定されたデータフォーマットへデータをエクスポートできます。 |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | 画像エクスポーターディスクリプタを表します。エクスポーターディスクリプタは、<br/>            各エクスポーターインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。 |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | 画像ローダー。 |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | 画像ローダーディスクリプタはローダーのプロパティを指定します。ローダーディスクリプタは、<br/>            各画像ローダーインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。 |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | インデックス画像フォーマット用のカラ―コンバータ。 |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | キーを持つオブジェクトのインターフェイスを表します。 |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | 境界を持つオブジェクトを表します。 |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | 順序付きシェイプを表します。順序付きシェイプは開始点と終了点を持つ連続した点の集合です。<br/>            特定の規則で接続された連続点の集合です。 |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | 部分的に読み込まれた 32 ビット ARGB ピクセルに準拠します。 |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | 64 ビット ARGB ピクセルローダー。 |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | 部分的に読み込まれたピクセルに準拠します。 |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | 部分データローダー。 |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | pasd カラーパレット |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | ラスタ画像 32 ビット ARGB ピクセルローダー。 |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | ラスタ画像ピクセルローダー。 |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | ラスタ画像生データローダー。 |
| [Image](/psd/python-net/aspose.psd/image/) | 画像はすべての画像タイプの基底クラスです。 |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) オブジェクトは、レンダリング中にビットマップとメタファイルの色がどのように操作されるかに関する情報を含みます。[ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) オブジェクトは、カラー調整行列、グレースケール調整行列、ガンマ補正値、カラーマップテーブル、カラースレッショルド値など、複数のカラー調整設定を保持します。レンダリング中に、色は補正、暗く、明るく、除去することができます。このような操作を適用するには、[ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) オブジェクトを初期化し、その [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) オブジェクトのパス（および [Image](/psd/python-net/aspose.psd/image/) のパス）を DrawImage メソッドに渡します。 |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | 画像クリエイターのレジストリを表します。 |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | 画像エクスポーターのレジストリを表します。 |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | 画像ローダーのレジストリを表します。 |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | 画像の基本オプション。 |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | 画像リサイズ設定クラス |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | 要素のシーケンスを表すクラス |
| [License](/psd/python-net/aspose.psd/license/) | コンポーネントのライセンスを付与するメソッドを提供します。 |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | ロードオプションを表します。 |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | GDI+ マトリックスを置き換えます。 |
| [Metered](/psd/python-net/aspose.psd/metered/) | メーターキーを設定するメソッドを提供します。 |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | 非ジェネリック辞書を表します。 |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | オブジェクトの非ジェネリックリスト |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | 境界を持つオブジェクト。 |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | システムにインストールされている OpenType フォントのキャッシュ。 |
| [Pen](/psd/python-net/aspose.psd/pen/) | 線、曲線、図形の描画に使用されるオブジェクトを定義します。 |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | ピクセルデータ形式。これは不変オブジェクトです。 |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | 画像ピクセルデータとその境界を格納するクラス。 |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | プラグイン ライセンス用例外 |
| [Point](/psd/python-net/aspose.psd/point/) | 2 次元平面上の点を定義する整数の x および y 座標の順序付きペアを表します。 |
| [PointF](/psd/python-net/aspose.psd/pointf/) | 2 次元平面上の点を定義する浮動小数点の x および y 座標の順序付きペアを表します。 |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | ラスタ画像で、ラスタグラフィック操作をサポートします。この画像は必要に応じてピクセルデータをキャッシュします。 |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | ラスタグラフィック操作をサポートするラスタ画像を表します。 |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | 生データ設定 |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | 矩形の位置とサイズを表す 4 つの整数のセットを格納します。 |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | 矩形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します。 |
| [Region](/psd/python-net/aspose.psd/region/) | 矩形とパスで構成されたグラフィック形状の内部を記述します。このクラスは継承できません。 |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | 画像保存オプションの解像度設定。 |
| [Shape](/psd/python-net/aspose.psd/shape/) | 形状。特定の規則で接続された連続した点の集合です。 |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | 形状セグメントを表します。セグメントは 2 点を結ぶ線または曲線です。 |
| [Size](/psd/python-net/aspose.psd/size/) | サイズを表します。 |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | 矩形の幅と高さなど、通常は浮動小数点数の順序付きペアを格納します。 |
| [Source](/psd/python-net/aspose.psd/source/) | ソースはオブジェクトパイプに関するすべての関連情報を保持するために使用されます。 |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | ストリームを保持し、ストリーム処理ルーチンを提供する分割ストリームコンテナを表します。 |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | ストリームを保持し、ストリーム処理ルーチンを提供するストリームコンテナを表します。 |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | テキストレイアウト情報（配置、向き、タブストップなど）や表示操作（省略記号の挿入や数字のローカライズ置換など）および OpenType 機能をカプセル化します。このクラスは継承できません。 |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | 透過性をサポートするオブジェクトです。 |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | ベクター画像はすべてのベクター画像タイプの基底クラスです。 |
## **Enumerations**
| **列挙** | **説明** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | 使用するキャッシュのタイプを指定します。 |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | 使用される文字セットを表します。 |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | どのオブジェクトがカラー調整情報を使用するかを指定します。 |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | CMYK（シアン、マゼンタ、イエロー、ブラック）カラースペースの個々のチャンネルを指定します。この列挙は SetOutputChannel メソッドで使用されます。 |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | 最近傍に調整するためのカラー比較方法 |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | 画像とカラーの調整設定およびグレースケール調整設定の影響を受ける画像とカラーのタイプを [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) で指定します。 |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | カラーの量子化手法 |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | 合成中に使用する品質レベルを指定します。 |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | 破線の各ダッシュの両端に使用するグラフィック形状のタイプを指定します。 |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | [Pen](/psd/python-net/aspose.psd/pen/) オブジェクトで描画される破線のスタイルを指定します。 |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | データ復旧モードです。 |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | ディザリング手法です。 |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | カラー変換を制御するために使用されるディザリング手法です。 |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | サポートされている PSD ファイル形式の一つです。 |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | 閉じたパスの内部がどのように塗りつぶされるかを指定します。 |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | テキストに適用されるスタイル情報を指定します。 |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | 指定されたデータの測定単位を指定します。 |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/) オブジェクトで利用可能なさまざまなパターンを指定します。 |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | テキストに関連するホットキー接頭辞の表示タイプを指定します。 |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | 使用する画像フィルター |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | この [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) 列挙体は、画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。 |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | 既知のシステムカラーを指定します。 |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | ラインの終端に使用できる [Pen](/psd/python-net/aspose.psd/pen/) オブジェクトの利用可能なキャップスタイルを指定します。 |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) オブジェクトに含まれる図形（サブパス）内の連続する直線または曲線セグメントをどのように結合するかを指定します。 |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | 行列変換操作の順序を指定します。 |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | 出力ファイルの PDF 準拠レベルを指定します。 |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | [Pen](/psd/python-net/aspose.psd/pen/) オブジェクトが理論上の幅ゼロの線に対してどのように配置されるかを指定します。 |
| [PenType](/psd/python-net/aspose.psd/pentype/) | [Pen](/psd/python-net/aspose.psd/pen/) オブジェクトがラインを塗りつぶす際に使用する塗りタイプを指定します。 |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | ピクセルデータ形式の実際の意味です。 |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | リサイズのタイプを指定します。 |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | 解像度単位列挙体。 |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | 画像がどれだけ回転するか、そして画像を反転させる際に使用される軸を指定します。 |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | シーク用に [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 内の参照ポイントを表すフィールドを提供します。 |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | ラインや曲線、塗りつぶし領域のエッジに対してスムージング（アンチエイリアシング）が適用されるかどうかを指定します。 |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | テキスト文字列がレイアウト矩形に対してどのように配置されるかを指定します。 |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | この列挙体は、ユーザーのロケールまたは言語に従って文字列内の数字を置換する方法を指定します。 |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | テキスト文字列の表示およびレイアウト情報を指定します。 |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | レイアウト形状に完全に収まらない文字列から文字をどのようにトリミングするかを指定します。 |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | テキストレンダリングの品質を指定します。 |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | 適用されるワープ変換のタイプを指定します。 |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | テクスチャまたはグラデーションが塗りつぶし領域より小さい場合のタイル配置方法を指定します。 |
