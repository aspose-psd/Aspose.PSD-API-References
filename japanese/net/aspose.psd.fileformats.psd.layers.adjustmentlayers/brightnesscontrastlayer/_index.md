---
title: Class BrightnessContrastLayer
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.BrightnessContrastLayer クラス. 明るさ/コントラスト レイヤー
type: docs
weight: 1680
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/
---
## BrightnessContrastLayer class

明るさ/コントラスト レイヤー。

```csharp
public class BrightnessContrastLayer : AdjustmentLayer
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | パレットを自動調整するかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | ピクセルあたりの画像ビット数を取得します。 |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | ブレンド オプションを取得します。 |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | ブレンド モード キーを取得または設定します。 |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | ブレンド モード シグネチャを取得します。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | 最下層の位置を取得または設定します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [Brightness](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/brightness/) { get; set; } | 明るさを取得または設定します。 PS の明るさの範囲は -150 から +150 です。しかし、これは無視します. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | チャネル情報を取得または設定します。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | レイヤーのチャンネル数を取得します。 |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | レイヤーのクリッピングを取得または設定します。 0 = ベース、1 = 非ベース. |
| [Container](../../aspose.psd/image/container/) { get; } | を取得します[`Image`](../../aspose.psd/image/)コンテナ. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/contrast/) { get; set; } | コントラストを取得または設定します。 PS の場合、コントラストの範囲は -50 から +100 です。しかし、これは無視します. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータ ストリームを取得します。 |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | レイヤーの表示名を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | レイヤーの付加情報の長さをバイト単位で取得します. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | ファイル形式の値を取得 |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | レイヤー フィラーを取得または設定します。 |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | 塗りつぶしの不透明度を取得または設定します。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | レイヤー フラグを取得または設定します。 ビット 0 = 透明度が保護されています。 ビット 1 = 表示されています。 ビット 2 = 廃止されています。 ビット 3 = Photoshop 5.0 以降では 1 であり、ビット 4 に有用な情報があるかどうかを示します。 ビット 4 =ドキュメントの外観に関係のないピクセル データ. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | このインスタンスがアルファを持っているかどうかを示す値を取得します. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 画像に透明色があるかどうかを示す値を取得します. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | 画像の高さを取得します. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | 水平方向の解像度を取得または設定します (1 インチあたりのピクセル数)。[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | この画像の不透明度を取得します。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 画像データが現在キャッシュされているかどうかを示す値を取得します。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 生データの読み込みが可能かどうかを示す値を取得します。 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | レイヤーが可視かどうかを示す値を取得または設定します |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | このインスタンスがグループ内で可視かどうかを示す値を取得します (レイヤーがグループ内にない場合は、ルート グループを意味します)。 |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | レイヤーのブレンド範囲データを取得または設定します. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | レイヤーの作成日時を取得または設定します。 |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | レイヤー ロックを取得または設定します。 フラグ LayerFlags.TransparencyProtected が設定されている場合、レイヤー ロック フラグによって上書きされることに注意してください。 |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | レイヤー マスク データを取得または設定します。 |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | レイヤ オプションを取得します。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | 左レイヤーの位置を取得または設定します. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | レイヤー全体の長さをバイト単位で取得します。 |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | レイヤー名を取得または設定します。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | レイヤーの不透明度を取得または設定します。 0 = 透明、255 = 不透明. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラー パレットを取得または設定します。ピクセルが直接表現されている場合、カラー パレットは使用されません。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 画像コンポーネントをあらかじめ乗算する必要があるかどうかを示す値を取得または設定します. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | カスタム カラー コンバーターを取得または設定します |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 生データ形式を取得します。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 現在の生データ設定を取得します。これらの設定を使用する場合、データは変換されずに読み込まれることに注意してください。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | パレット インデックスが範囲外の場合に使用するフォールバック インデックスを取得または設定します |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | インデックス付きカラー コンバーターを取得または設定します |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 生の行サイズをバイト単位で取得します。 |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | レイヤー リソースを取得または設定します。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | 正しいレイヤー位置を取得または設定します。 |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | レイヤーのリストで装飾シートの色のハイライトを取得または設定します |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | 最上層の位置を取得または設定します。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 画像の透明色を取得します. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP メタデータを更新するかどうかを示す値を取得または設定します。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 生データの読み込みが可能な場合に、生データの読み込みを使用するかどうかを示す値を取得または設定します。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | この解像度の垂直方向の解像度 (1 インチあたりのピクセル数) を取得または設定します[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | 画像の幅を取得します. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP メタデータを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | マスクを現在のレイヤーに追加します。 |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | 画像の明るさを調整します。 |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | 画像のコントラスト |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | 画像のガンマ補正. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | 画像のガンマ補正. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | インテグラル イメージしきい値処理を使用した Bradley の適応しきい値処理アルゴリズムを使用したイメージの 2 値化 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | インテグラル イメージしきい値処理を使用した Bradley の適応しきい値処理アルゴリズムを使用したイメージの 2 値化 |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | 事前定義されたしきい値による画像の 2 値化 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | 大津閾値処理による画像の二値化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | データをキャッシュし、基盤から追加のデータ読み込みが実行されないようにします[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式で画像を保存できるかどうかを決定します。 |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | 画像をトリミングしています。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | シフトで画像をトリミングします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 現在の画像でディザリングを実行します。 |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 現在の画像でディザリングを実行します。 |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | レイヤーに画像を描画します。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 指定された四角形をフィルタリングします。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトのオプションを取得します。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 部分ピクセル ローダーを使用してデフォルトのピクセル配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | デフォルトの生データ配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 部分ピクセル ローダーを使用して、デフォルトの生データ配列を取得します。 |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | このインスタンスのハッシュ コードを返します。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | リソース イメージが最後に変更された日時を取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づいてオプションを取得します. これは、元の画像のビット深度やその他のパラメーターを変更しないで保持するのに役立ちます. たとえば、1 ビットあたり 1 ビットの白黒 PNG 画像をロードし、 the を使用して保存します[`Save`](../../aspose.psd/datastreamsupporter/save/) これを回避し、1 ピクセルあたり 1 ビットの PNG 画像を保存するには、このメソッドを使用して対応する保存オプションを取得し、 を[`Save`](../../aspose.psd/image/save/) 番目のパラメーターとしてのメソッド。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 画像ピクセルを取得します。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 傾斜角度を取得します。 このメソッドは、スキャン時の傾斜角度を決定するために、スキャンされたテキスト ドキュメントに適用されます。 |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | グレースケール表現への画像の変換 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32 ビット ARGB ピクセルをロードします。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64 ビット ARGB ピクセルをロードします。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | ピクセルを CMYK 形式で読み込みます。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32 ビット ARGB ピクセルを部分的にパックで読み込みます。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | パック単位で部分的にピクセルを読み込みます。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | ピクセルを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | レイヤーを指定したレイヤーに結合します |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 角度を正規化します。 この方法は、スキャンされたテキスト ドキュメントに適用され、スキャンの歪みを取り除きます。 この方法は、[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)と[`Rotate`](../../aspose.psd/rasterimage/rotate/)メソッド. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 角度を正規化します。 この方法は、スキャンされたテキスト ドキュメントに適用され、スキャンの歪みを取り除きます。 この方法は、[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)と[`Rotate`](../../aspose.psd/rasterimage/rotate/)メソッド. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 指定されたスキャン ライン インデックスでスキャン ライン全体を読み取ります。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 指定されたスキャン ライン インデックスでスキャン ライン全体を読み取ります。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | ある色を別の許容差で置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | ある色を別の許容差で置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | すべての不透明な色を新しい色に置き換え、元のアルファ値を維持して滑らかなエッジを保存します。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | すべての不透明な色を新しい色に置き換え、元のアルファ値を維持して滑らかなエッジを保存します。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトLeftTopToLeftTop使用されています. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 高さを比例してサイズ変更します。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 幅を比例してサイズ変更します。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | 画像を中心に回転します。 |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | 画像を中心に回転します。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 画像を回転、反転、または回転して反転します。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32 ビット ARGB ピクセルを保存します。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | ピクセルを保存します。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | ピクセルを保存します。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 生データを保存します。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 指定された位置に画像の 32 ビット ARGB ピクセルを設定します。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 画像パレットを設定します。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 指定された位置にイメージ ピクセルを設定します。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | この解像度を設定します[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | 現在のレイヤーの浅いコピーを作成します. してください[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx)説明用. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | ラスター イメージをビットマップに変換します。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | スキャン ライン全体を指定されたスキャン ライン インデックスに書き込みます。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | スキャン ライン全体を指定されたスキャン ライン インデックスに書き込みます。 |

### 関連項目

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [AdjustmentLayer](../adjustmentlayer/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* 組み立て [Aspose.PSD](../../)


