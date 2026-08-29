---
title: "クラス PsdImage"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.PsdImage クラス。PSD ファイルの読み込み、編集、保存、およびプロパティの更新、透かしの追加、グラフィック操作の実行、またはファイル形式の相互変換を可能にする PsdImage クラスを定義します。Aspose.PSD はレイヤーとしてのインポートと、次の形式へのエクスポートをサポートします：Png、Jpeg、Jpeg2000、Gif、Bmp、Tiff、Psd、Psb、さらに選択可能なテキストを含む Pdf へのエクスポートもサポートします。"
type: docs
weight: 4050
url: /ja/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

PsdImage クラスは、PSD ファイルの読み込み、編集、保存に加えてプロパティの更新、透かしの追加、グラフィック操作の実行、またはファイル形式を別の形式に変換する機能を提供します。Aspose.PSD はレイヤーとしてのインポートをサポートし、次の形式へのエクスポートが可能です：Png、Jpeg、Jpeg2000、Gif、Bmp、Tiff、Psd、Psb、さらに選択可能なテキストを含む Pdf へのエクスポートもサポートします。

```csharp
public sealed class PsdImage : RasterCachedImage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | `PsdImage` クラスの新しいインスタンスを、既存のラスタ画像（PSD 画像ではない）から、RGB カラーモード、4 チャンネル、8 ビット/チャンネル、圧縮なしで初期化します。 |
| [PsdImage](psdimage/#constructor_4)(Stream) | 指定されたパスのラスタ画像（ストリーム内の PSD 画像ではない）から `PsdImage` クラスの新しいインスタンスを初期化します。デフォルトパラメータで PSD 画像を初期化するために使用します - カラーモード: rgb、4 チャンネル、8 ビット/チャンネル、圧縮: Raw。 |
| [PsdImage](psdimage/#constructor_6)(string) | 指定されたパスのラスタ画像（パス上の PSD 画像ではない）から `PsdImage` クラスの新しいインスタンスを初期化します。デフォルトパラメータで PSD 画像を初期化するために使用します - カラーモード: rgb、4 チャンネル、8 ビット/チャンネル、圧縮: Raw。 |
| [PsdImage](psdimage/#constructor_2)(int, int) | 指定された幅と高さで `PsdImage` クラスの新しいインスタンスを初期化します。空の PSD 画像を初期化するために使用します。 |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | 既存のラスタ画像（PSD 画像ではない）からコンストラクタパラメータを使用して `PsdImage` クラスの新しいインスタンスを初期化します。 |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | 指定されたパスのラスタ画像（ストリーム内の PSD 画像ではない）からコンストラクタパラメータを使用して `PsdImage` クラスの新しいインスタンスを初期化します。 |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | 指定されたパスのラスタ画像（パス内のpsd画像ではなく）から、コンストラクタ パラメータを使用して `PsdImage` クラスの新しいインスタンスを初期化します。 |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | 指定された幅、高さ、パレット、カラーモード、チャンネル数およびチャンネルビット長、さらに指定された圧縮モード パラメータを使用して `PsdImage` クラスの新しいインスタンスを初期化します。空の psd 画像を初期化するために使用されます。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | アクティブ レイヤーを取得または設定します。 |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 自動調整パレットかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | チャンネルあたりのビット数を取得します。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | 画像のピクセルあたりのビット数を取得します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | PSD のチャンネル数を取得します。 |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | CMYK PSD 画像の CMYK カラープロファイルを取得または設定します。正しい色変換のために RgbColorProfile とペアで使用する必要があります。 |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | カラーモードを取得または設定します。 |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | 圧縮方法を取得します。 |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../../aspose.psd/image/) コンテナを取得します。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | ファイル形式の値を取得します。 |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | グローバル角度を取得または設定します。 |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | グローバル レイヤーマスク情報を取得します。 |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | グローバル レイヤーリソースを取得または設定します。 |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | グレースケール PSD 画像の GRAY（モノクロ）カラープロファイルを取得または設定します。 |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | この [`RasterImage`](../../aspose.psd/rasterimage/) の垂直解像度（インチあたりピクセル数）を取得または設定します。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | レイヤーデータを指定したときに、最初のアルファチャンネルが合成結果の透過データを含むかどうかを示す値を取得または設定します。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 画像に透明色があるかどうかを示す値を取得します。 |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | 画像の高さを取得します。 |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | この `PsdImage` の水平解像度（インチあたりのピクセル数）を取得または設定します。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | この画像の不透明度を取得します。 |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | PSD 画像リソースを取得または設定します。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 画像データが現在キャッシュされているかどうかを示す値を取得します。 |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | PSD 画像がフラット化されているかどうかを示す値を取得します。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 生データのロードが利用可能かどうかを示す値を取得します。 |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | PSD レイヤーを取得または設定します。 |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | リンクされたレイヤーマネージャーを取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 画像コンポーネントが事前乗算されている必要があるかどうかを示す値を取得または設定します。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | カスタムカラーコンバータを取得または設定します |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | 生データ形式を取得します。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 現在の生データ設定を取得します。これらの設定を使用すると、データは変換せずにロードされることに注意してください。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | インデックスカラーコンバータを取得または設定します |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 生ラインサイズ（バイト単位）を取得します。 |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | CMYK PSD 画像の RGB カラープロファイルを取得または設定します。正しい色変換のために CmykColorProfile とペアで使用する必要があります。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | スマートオブジェクトプロバイダーを取得します。 |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | `PsdImage` の [`Timeline`](./timeline/) を取得します。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 画像の透過色を取得します。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMPメタデータを更新するかどうかを示す値を取得または設定します。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 画像パレットが使用されているかどうかを示す値を取得します。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 生データロードが利用可能な場合に、生データロードを使用するかどうかを示す値を取得または設定します。 |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | バージョンを取得または設定します。 |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | この `PsdImage` の垂直解像度（インチあたりのピクセル数）を取得または設定します。 |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | 画像の幅を取得します。 |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | XMPメタデータを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | 白黒調整レイヤーを追加します。 |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | 明るさ/コントラスト調整レイヤーを追加します。 |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | デフォルト パラメータでチャンネルミキサー調整レイヤーを追加します。 |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | カラーバランス調整レイヤーを追加します。 |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | カーブ調整レイヤーを追加します。 |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | 露出調整レイヤーを追加します。 |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | GradientMap 調整レイヤーを追加します。 |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | 色相/彩度調整レイヤーを追加します。 |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | 反転調整レイヤーを追加します。 |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | レイヤーを追加します。 |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | レイヤー グループを追加します。 |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | レベル調整レイヤーを追加します。 |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | PhotoFilter レイヤーを追加します。 |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Posterize 調整レイヤーを追加します。 |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | 新しい通常レイヤーを追加します。 |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | 選択カラー調整レイヤーを追加します。 |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | 空の Shape レイヤーを追加します。パスはありません。保存前にシェイプレイヤーに追加する必要があります。 |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | 新しいテキストレイヤーを追加します。 |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | しきい値調整レイヤーを追加します。 |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | バイブランス調整レイヤーを追加します。 |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | 画像の明るさを調整します。 |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | 画像のコントラスト調整 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | 画像のガンマ補正。 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | 画像のガンマ補正。 |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Bradley の適応的閾値アルゴリズム（積分画像閾値）を使用した画像の二値化 |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Bradley の適応的閾値アルゴリズム（積分画像閾値）を使用した画像の二値化 |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | 事前定義されたしきい値を使用した画像の二値化 |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Otsuしきい値処理による画像の二値化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | データをキャッシュし、基になる [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) から追加のデータ読み込みが行われないことを保証します。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | この画像形式をオプションで指定された形式に変換します。 |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | 画像のトリミング。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | シフト付きで画像をトリミングします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 現在の画像にディザ処理を実行します。 |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 現在の画像にディザ処理を実行します。 |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | 指定された矩形をフィルタリングします。 |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | すべてのレイヤーを統合します。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトオプションを取得します。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | デフォルトの生データ配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | リソース画像が最後に変更された日時を取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づくオプションを取得します。これにより、元画像のビット深度やその他のパラメータを変更せずに保持できます。例えば、1 ビット/ピクセルの白黒 PNG 画像を読み込み、[`Save`](../../aspose.psd/datastreamsupporter/save/) メソッドで保存すると、8 ビット/ピクセルの PNG 画像が出力されます。これを回避し、1 ビット/ピクセルの PNG 画像として保存するには、このメソッドで対応する保存オプションを取得し、[`Save`](../../aspose.psd/image/save/) メソッドの第2パラメータとして渡します。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 画像のピクセルを取得します。パフォーマンス警告: すべての画像ピクセルを反復処理するためにこのメソッドを使用すると、重大なパフォーマンス問題が発生する可能性があります。より効率的なピクセル操作のためには、`LoadArgb32Pixels` メソッドを使用してピクセル配列全体を一度に取得してください。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 傾き角度を取得します。このメソッドはスキャンされたテキスト文書に適用でき、スキャン時の傾き角度を判定します。 |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | 画像をグレースケール表現に変換する |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32ビット ARGB ピクセルを読み込みます。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64ビット ARGB ピクセルを読み込みます。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK 形式のピクセルを読み込みます。 |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK 形式のピクセルを読み込みます。このメソッドは非推奨です。より効果的な [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) メソッドを使用してください。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32ビット ARGB ピクセルをパック単位で部分的に読み込みます。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | ピクセルをパック単位で部分的に読み込みます。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | ピクセルを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | レイヤーを結合します。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 角度を正規化します。このメソッドはスキャンされたテキスト文書の歪みを除去するために適用できます。このメソッドは [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) と [`Rotate`](../../aspose.psd/rasterimage/rotate/) メソッドを使用します。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 角度を正規化します。このメソッドはスキャンされたテキスト文書の歪みを除去するために適用できます。このメソッドは [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) と [`Rotate`](../../aspose.psd/rasterimage/rotate/) メソッドを使用します。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 指定されたスキャンラインインデックスでスキャンライン全体を読み取ります。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 指定されたスキャンラインインデックスでスキャンライン全体を読み取ります。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 許容差を持たせてある色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。 |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | 許容差を持たせてある色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明度のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明度のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトの NearestNeighbourResample が使用されます。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例的にリサイズします。 |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 高さを比例的にリサイズします。 |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 高さを比例的にリサイズします。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例的にリサイズします。デフォルトの NearestNeighbourResample が使用されます。 |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 幅を比例的にリサイズします。 |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 幅を比例的にリサイズします。 |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | 画像を中心を基準に回転させます。 |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | 画像を中心を基準に回転させます。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 画像を回転、フリップ、または回転とフリップを行います。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32ビット ARGB ピクセルを保存します。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | ピクセルを保存します。 |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | ピクセルを保存します。このメソッドは非推奨です。より効果的な[`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/)メソッドを使用してください。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | ピクセルを保存します。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 生データを保存します。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 指定された位置に画像の 32 ビット ARGB ピクセルを設定します。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 画像のパレットを設定します。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 指定された位置に画像ピクセルを設定します。 |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | `PsdImage` の解像度を設定します。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | ラスタ画像をビットマップに変換します。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | デフォルトの PSD バージョンです。 |

## 例

以下のコードは、特定の角度値で画像を回転させる機能を示しています。

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 画像全体の回転
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// レイヤーの回転
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### 関連項目

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


