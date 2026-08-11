---
title: "Aspose.PSD"
second_title: "Aspose.PSD for .NET API Reference"
description: "この名前空間は、入れ子になった名前空間のコアであり、Aspose.PSD 処理に使用される最も基本的なオブジェクトです。"
type: docs
weight: 10
url: /ja/net/aspose.psd/
---
{{< psd/tize >}}
この名前空間は、入れ子になった名前空間のコアであり、Aspose.PSD の処理に使用される最も基本的なオブジェクトです。

## クラス

| クラス | 説明 |
| --- | --- |
| [AggregateException](./aggregateexception/) | 複数の例外を集約します。 |
| [Blend](./blend/) | ブレンドパターンを定義します。このクラスは継承できません。 |
| [Brush](./brush/) | 基本ブラシクラスです。 |
| [BuildVersionInfo](./buildversioninfo/) | 現在のビルドバージョン情報を含みます。 |
| [Cache](./cache/) | キャッシュ設定を含みます。 |
| [CmykColorHelper](./cmykcolorhelper/) | 符号付き 32 ビット整数値として表現された CMYK カラーを操作するヘルパーメソッドです。[`CmykColor`](../aspose.psd/cmykcolor/) 構造体と同様の API を提供します。CMYK カラーが内部フィールドを持つ構造体ではなく Int32 として表現されるため、より軽量です。可能な限り、非推奨の [`CmykColor`](../aspose.psd/cmykcolor/) 構造体の代わりにこのクラスの静的メソッドを使用してください。 |
| [ColorBlend](./colorblend/) | マルチカラーグラデーションでの色ブレンド補間に使用される色と位置の配列を定義します。このクラスは継承できません。 |
| [ColorMap](./colormap/) | 色変換用のマップを定義します。[`ImageAttributes`](../aspose.psd/imageattributes/) クラスのいくつかのメソッドは、[`ColorMap`](../aspose.psd/colormap/) 構造体の配列であるカラーリマップテーブルを使用して画像の色を調整します。継承できません。 |
| [ColorMatrix](./colormatrix/) | RGBA 空間の座標を含む 5×5 行列を定義します。[`ImageAttributes`](../aspose.psd/imageattributes/) クラスのいくつかのメソッドは、カラー行列を使用して画像の色を調整します。このクラスは継承できません。 |
| [ColorPalette](./colorpalette/) | カラーパレットを構成する色の配列を定義します。これらの色は 32 ビット ARGB カラーです。継承できません。 |
| [ColorPaletteHelper](./colorpalettehelper/) | カラーパレット操作のためのヘルパークラスです。 |
| [ColorTranslator](./colortranslator/) | GDI+ Color 構造体との間で色を変換します。このクラスは継承できません。 |
| [CompositeException](./compositeexception/) | 複合例外 |
| [CustomLineCap](./customlinecap/) | カスタムのユーザー定義ラインキャップをカプセル化します。 |
| [DataStreamSupporter](./datastreamsupporter/) | データストリームコンテナ。 |
| [DisposableObject](./disposableobject/) | 破棄可能なオブジェクトを表します。 |
| [Figure](./figure/) | 図。形状のコンテナです。 |
| [FileStreamContainer](./filestreamcontainer/) | ファイルストリーム処理のヘルパー。 |
| [Font](./font/) | フォントの種類、サイズ、スタイル属性を含むテキストの特定の形式を定義します。このクラスは継承できません。 |
| [FontSettings](./fontsettings/) | 一般的な PSD ベクターフォーマットレンダラのフォント設定。 |
| [Graphics](./graphics/) | 現在のアセンブリで使用されているグラフィックエンジンに従ってグラフィックを表します。 |
| [GraphicsPath](./graphicspath/) | 接続された直線と曲線の系列を表します。このクラスは継承できません。 |
| [Image](./image/) | 画像はすべての画像タイプの基底クラスです。 |
| [ImageAttributes](./imageattributes/) | [`ImageAttributes`](../aspose.psd/imageattributes/) オブジェクトは、レンダリング中にビットマップとメタファイルの色がどのように操作されるかに関する情報を含みます。[`ImageAttributes`](../aspose.psd/imageattributes/) オブジェクトは、カラー調整行列、グレースケール調整行列、ガンマ補正値、カラーマップテーブル、カラーしきい値など、複数のカラー調整設定を保持します。レンダリング中に、色は補正、暗く、明るく、除去することができます。このような操作を適用するには、[`ImageAttributes`](../aspose.psd/imageattributes/) オブジェクトを初期化し、その [`ImageAttributes`](../aspose.psd/imageattributes/) オブジェクトのパス（[`Image`](../aspose.psd/image/) のパスと共に）を DrawImage メソッドに渡します。 |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | 画像作成者レジストリを表します。 |
| [ImageExportersRegistry](./imageexportersregistry/) | 画像エクスポーター レジストリを表します。 |
| [ImageLoadersRegistry](./imageloadersregistry/) | 画像ローダー レジストリを表します。 |
| [ImageOptionsBase](./imageoptionsbase/) | 画像の基本オプション。 |
| [ImageResizeSettings](./imageresizesettings/) | 画像リサイズ設定クラス |
| [IntRange](./intrange/) | 要素のシーケンスを表すクラス |
| [License](./license/) | コンポーネントのライセンスを付与するメソッドを提供します。 |
| [LoadOptions](./loadoptions/) | ロードオプションを表します。 |
| [Matrix](./matrix/) | GDI+ マトリックスを置き換えます。 |
| [Metered](./metered/) | メーターキーを設定するメソッドを提供します。 |
| [NonGenericDictionary](./nongenericdictionary/) | 非ジェネリック辞書を表します。 |
| [NonGenericList](./nongenericlist/) | オブジェクトの非ジェネリックリスト |
| [ObjectWithBounds](./objectwithbounds/) | 境界を持つオブジェクト。 |
| [OpenTypeFontsCache](./opentypefontscache/) | システムにインストールされている OpenType フォントのキャッシュ。 |
| [Pen](./pen/) | 線、曲線、図形の描画に使用されるオブジェクトを定義します。 |
| [PixelDataFormat](./pixeldataformat/) | ピクセルデータ形式です。これは不変オブジェクトです。 |
| [PixelsData](./pixelsdata/) | 画像ピクセルデータとその境界を格納するクラスです。 |
| [PluginLicenseException](./pluginlicenseexception/) | プラグインライセンス用例外 |
| [ProgressEventHandler](./progresseventhandler/) | 進捗イベントハンドラ関数の参照 |
| [RasterCachedImage](./rastercachedimage/) | ラスターグラフィック操作をサポートするラスター画像を表します。必要に応じてこの画像はピクセルデータをキャッシュします。 |
| [RasterImage](./rasterimage/) | ラスターグラフィック操作をサポートするラスター画像を表します。 |
| [RawDataSettings](./rawdatasettings/) | 生データ設定 |
| [Region](./region/) | 矩形とパスで構成されたグラフィックシェイプの内部を記述します。このクラスは継承できません。 |
| [ResolutionSetting](./resolutionsetting/) | 画像保存オプションの解像度設定です。 |
| [Shape](./shape/) | シェイプです。特定の規則で接続された連続した点の集合です。 |
| [ShapeSegment](./shapesegment/) | シェイプセグメントを表します。セグメントは2点を結ぶ直線または曲線です。 |
| [Source](./source/) | ソースはオブジェクトパイプに関するすべての関連情報を保持するために使用されます。 |
| [SplitStreamContainer](./splitstreamcontainer/) | ストリームを保持し、ストリーム処理ルーチンを提供する分割ストリームコンテナを表します。 |
| [StreamContainer](./streamcontainer/) | ストリームを保持し、ストリーム処理ルーチンを提供するストリームコンテナを表します。 |
| [StringFormat](./stringformat/) | テキストレイアウト情報（配置、向き、タブストップなど）や表示操作（省略記号の挿入や数字のローカライズ置換など）および OpenType 機能をカプセル化します。このクラスは継承できません。 |
| [TransparencySupporter](./transparencysupporter/) | 透過性をサポートするオブジェクトです。 |
| [VectorImage](./vectorimage/) | ベクター画像はすべてのベクター画像タイプの基底クラスです。 |
## Structures

| 構造 | 説明 |
| --- | --- |
| [CmykColor](./cmykcolor/) | ピクセルの CMYK カラーです。 |
| [Color](./color/) | ピクセルの色です。 |
| [Point](./point/) | 2 次元平面上の点を定義する整数の x および y 座標の順序付きペアを表します。 |
| [PointF](./pointf/) | 2 次元平面上の点を定義する浮動小数点の x および y 座標の順序付きペアを表します。 |
| [Rectangle](./rectangle/) | 矩形の位置とサイズを表す 4 つの整数のセットを格納します。 |
| [RectangleF](./rectanglef/) | 矩形の位置とサイズを表す4つの浮動小数点数のセットを格納します。 |
| [Size](./size/) | サイズを表します。 |
| [SizeF](./sizef/) | 通常は矩形の幅と高さとなる、順序付けられた浮動小数点数のペアを格納します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | 高度なバッファプロセッサ。 |
| [IBufferProcessor](./ibufferprocessor/) | バッファプロセッサ。 |
| [IColorConverter](./icolorconverter/) | カラーコンバータ。 |
| [IColorPalette](./icolorpalette/) | カラーパレットインターフェイス。 |
| [IImageCreator](./iimagecreator/) | 画像クリエイター。 |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | 画像クリエイターディスクリプタはクリエイターのプロパティを指定します。クリエイターディスクリプタは、各画像クリエイターインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。 |
| [IImageDescriptor](./iimagedescriptor/) | 画像ディスクリプタです。すべての他の画像ディスクリプタタイプの基本プロパティとメソッドを含みます。 |
| [IImageExporter](./iimageexporter/) | 画像エクスポーターです。内部の Aspose.PSD フォーマットから指定されたデータ形式へデータをエクスポートできます。 |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | 画像エクスポーターディスクリプタを表します。エクスポーターディスクリプタは、各エクスポーターインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。 |
| [IImageLoader](./iimageloader/) | 画像ローダー。 |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | 画像ローダーディスクリプタはローダーのプロパティを指定します。ローダーディスクリプタは、各画像ローダーインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。 |
| [IIndexedColorConverter](./iindexedcolorconverter/) | インデックス画像フォーマット用のカラーコンバータ。 |
| [IKeyedObject](./ikeyedobject/) | キーを持つオブジェクトのインターフェイスを表します。 |
| [IObjectWithBounds](./iobjectwithbounds/) | 境界を持つオブジェクトを表します。 |
| [IOrderedShape](./iorderedshape/) | 順序付けられたシェイプを表します。順序付けられたシェイプは、開始点と終了点を持つ連続した点の集合です。特定の規則を使用して接続された連続点の集合です。 |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | 部分的に読み込まれた32ビット ARGB ピクセルに準拠しています。 |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | 64ビット ARGB ピクセルローダー。 |
| [IPartialPixelLoader](./ipartialpixelloader/) | 部分的に読み込まれたピクセルに準拠しています。 |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | 部分データローダー。 |
| [IPsdColorPalette](./ipsdcolorpalette/) | pasd カラーパレット |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | ラスタ画像 32ビット ARGB ピクセルローダー。 |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | ラスタ画像ピクセルローダー。 |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | ラスタ画像の生データローダー。 |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [CacheType](./cachetype/) | 使用するキャッシュタイプを指定します。 |
| [CharacterSet](./characterset/) | 使用される文字セットを表します。 |
| [ColorAdjustType](./coloradjusttype/) | どのオブジェクトがカラー調整情報を使用するかを指定します。 |
| [ColorChannelFlag](./colorchannelflag/) | CMYK（シアン、マゼンタ、イエロー、ブラック）カラースペースの個々のチャンネルを指定します。この列挙は SetOutputChannel メソッドで使用されます。 |
| [ColorCompareMethod](./colorcomparemethod/) | 最近傍に調整するための色比較方法 |
| [ColorMatrixFlag](./colormatrixflag/) | カラーおよびグレースケール調整設定の影響を受ける画像と色のタイプを、[`ImageAttributes`](../aspose.psd/imageattributes/) で指定します。 |
| [ColorQuantizationMethod](./colorquantizationmethod/) | カラー量子化手法 |
| [CompositingQuality](./compositingquality/) | 合成中に使用する品質レベルを指定します。 |
| [DashCap](./dashcap/) | 破線の各ダッシュの両端で使用するグラフィック形状のタイプを指定します。 |
| [DashStyle](./dashstyle/) | [`Pen`](../aspose.psd/pen/) オブジェクトで描画される破線のスタイルを指定します。 |
| [DataRecoveryMode](./datarecoverymode/) | データ復旧モードです。 |
| [DitheringMethod](./ditheringmethod/) | ディザリング手法です。 |
| [DitheringMethods](./ditheringmethods/) | カラー変換を制御するために使用されるディザリング手法です。 |
| [FileFormat](./fileformat/) | サポートされている PSD ファイル形式の一つです。 |
| [FillMode](./fillmode/) | 閉じたパスの内部がどのように塗りつぶされるかを指定します。 |
| [FontStyle](./fontstyle/) | テキストに適用されるスタイル情報を指定します。 |
| [GraphicsUnit](./graphicsunit/) | 指定されたデータの測定単位を指定します。 |
| [HatchStyle](./hatchstyle/) | [`HatchBrush`](../aspose.psd.brushes/hatchbrush/) オブジェクトで利用可能なさまざまなパターンを指定します。 |
| [HotkeyPrefix](./hotkeyprefix/) | テキストに関連するホットキー接頭辞の表示タイプを指定します。 |
| [ImageFilterType](./imagefiltertype/) | 使用する画像フィルター |
| [InterpolationMode](./interpolationmode/) | [`InterpolationMode`](../aspose.psd/interpolationmode/) 列挙は、画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。 |
| [KnownColor](./knowncolor/) | 既知のシステムカラーを指定します。 |
| [LineCap](./linecap/) | [`Pen`](../aspose.psd/pen/) オブジェクトがラインの終端に使用できるキャップスタイルを指定します。 |
| [LineJoin](./linejoin/) | [`GraphicsPath`](../aspose.psd/graphicspath/) オブジェクトに含まれる図形（サブパス）内の連続する直線または曲線セグメントをどのように結合するかを指定します。 |
| [MatrixOrder](./matrixorder/) | 行列変換操作の順序を指定します。 |
| [PdfComplianceVersion](./pdfcomplianceversion/) | 出力ファイルの PDF 準拠レベルを指定します。 |
| [PenAlignment](./penalignment/) | 理論上の幅ゼロの線に対する [`Pen`](../aspose.psd/pen/) オブジェクトの配置を指定します。 |
| [PenType](./pentype/) | [`Pen`](../aspose.psd/pen/) オブジェクトが線を塗りつぶす際に使用する塗りタイプを指定します。 |
| [PixelFormat](./pixelformat/) | ピクセル データ形式の実際の意味です。 |
| [ResizeType](./resizetype/) | リサイズの種類を指定します。 |
| [ResolutionUnit](./resolutionunit/) | 解像度単位列挙体です。 |
| [RotateFlipType](./rotatefliptype/) | 画像が回転する角度と、画像を反転させる際に使用する軸を指定します。 |
| [SeekOrigin](./seekorigin/) | シーク用に [`StreamContainer`](../aspose.psd/streamcontainer/) 内の参照ポイントを表すフィールドを提供します。 |
| [SmoothingMode](./smoothingmode/) | 線や曲線、塗りつぶし領域のエッジに対してスムージング（アンチエイリアス）が適用されるかどうかを指定します。 |
| [StringAlignment](./stringalignment/) | テキスト文字列をレイアウト矩形に対して配置する位置を指定します。 |
| [StringDigitSubstitute](./stringdigitsubstitute/) | 列挙体は、ユーザーのロケールまたは言語に従って文字列内の数字を置換する方法を指定します。 |
| [StringFormatFlags](./stringformatflags/) | テキスト文字列の表示およびレイアウト情報を指定します。 |
| [StringTrimming](./stringtrimming/) | レイアウト形状に完全に収まらない文字列から文字をトリミングする方法を指定します。 |
| [TextRenderingHint](./textrenderinghint/) | テキストレンダリングの品質を指定します。 |
| [WarpMode](./warpmode/) | 適用されるワープ変換のタイプを指定します。 |
| [WrapMode](./wrapmode/) | テクスチャまたはグラデーションが塗りつぶし領域より小さい場合のタイル配置方法を指定します。 |


