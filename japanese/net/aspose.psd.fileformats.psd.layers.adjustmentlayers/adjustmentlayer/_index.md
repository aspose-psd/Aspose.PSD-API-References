---
title: "クラス AdjustmentLayer"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.AdjustmentLayer クラス。調整レイヤー。たとえば Brightness/contrast"
type: docs
weight: 1700
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/
---
{{< psd/tize >}}
## AdjustmentLayer class

調整レイヤー。例として明るさ/コントラストがあります。

```csharp
public abstract class AdjustmentLayer : Layer
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 自動調整パレットかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | 画像のピクセルあたりのビット数を取得します。 |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | クリップされた要素のブレンドを取得または設定します。 |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | ブレンドオプションを取得します。 |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | ブレンドモードキーを取得または設定します。 |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | ブレンドモードのシグネチャを取得します。 |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | 下層レイヤーの位置を取得または設定します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | チャンネル情報を取得または設定します。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | レイヤーのチャンネル数を取得します。 |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | レイヤーのクリッピングを取得または設定します。0 = ベース、1 = 非ベース。 |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../../aspose.psd/image/) コンテナを取得します。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータストリームを取得します。 |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | レイヤーの表示名を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | レイヤーの追加情報の長さ（バイト単位）を取得します。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | ファイル形式の値を取得します。 |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | レイヤーのフィラーを取得または設定します。 |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | 塗りつぶしの不透明度を取得または設定します。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | レイヤーフラグを取得または設定します。ビット0 = 透明保護; ビット1 = 表示; ビット2 = 旧式; ビット3 = Photoshop 5.0以降の場合は1で、ビット4に有用な情報があるかを示します; ビット4 = ドキュメントの外観に関係しないピクセルデータ。 |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | このインスタンスがアルファを持つかどうかを示す値を取得します。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 画像に透明色があるかどうかを示す値を取得します。 |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | 画像の高さを取得します。 |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | この[`RasterImage`](../../aspose.psd/rasterimage/)の水平解像度（インチあたりピクセル数）を取得または設定します。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | この画像の不透明度を取得します。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 画像データが現在キャッシュされているかどうかを示す値を取得します。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 生データのロードが利用可能かどうかを示す値を取得します。 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | レイヤーが表示されているかどうかを示す値を取得または設定します |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | このインスタンスがグループ内で表示されているかどうかを示す値を取得します（レイヤーがグループに属していない場合はルートグループを意味します）。 |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | レイヤーのブレンド範囲データを取得または設定します。 |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | レイヤーの作成日時を取得または設定します。 |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | レイヤーロックを取得または設定します。フラグ LayerFlags.TransparencyProtected が設定されている場合、レイヤーロックフラグによって上書きされることに注意してください。LayerFlags.TransparencyProtected フラグを返すには、レイヤーオプション layer.Flags &#x7C;= LayerFlags.TransparencyProtected を適用する必要があります。 |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | レイヤーマスクデータを取得または設定します。 |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | レイヤーオプションを取得します。 |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | 左側のレイヤー位置を取得または設定します。 |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | レイヤー全体の長さ（バイト単位）を取得します。 |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | レイヤー名を取得または設定します。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | レイヤーの不透明度を取得または設定します。0 = 透明、255 = 不透明。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 画像コンポーネントが事前乗算されている必要があるかどうかを示す値を取得または設定します。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | カスタムカラーコンバータを取得または設定します |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 生データ形式を取得します。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 現在の生データ設定を取得します。これらの設定を使用すると、データは変換せずにロードされることに注意してください。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | インデックスカラーコンバータを取得または設定します |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 生ラインサイズ（バイト単位）を取得します。 |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | レイヤーリソースを取得または設定します。 |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | 右側のレイヤー位置を取得または設定します。 |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | レイヤーリスト内の装飾シートカラーのハイライトを取得または設定します |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | 上部レイヤー位置を取得または設定します。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 画像の透過色を取得します。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMPメタデータを更新するかどうかを示す値を取得または設定します。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 画像パレットが使用されているかどうかを示す値を取得します。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 生データロードが利用可能な場合に、生データロードを使用するかどうかを示す値を取得または設定します。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | この [`RasterImage`](../../aspose.psd/rasterimage/) の垂直解像度（インチあたりピクセル数）を取得または設定します。 |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | 画像の幅を取得します。 |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMPメタデータを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | マスクを現在のレイヤーに追加します。 |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | 画像の明るさを調整します。 |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | 画像のコントラスト調整 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | 画像のガンマ補正。 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | 画像のガンマ補正。 |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | レイヤーマスクをレイヤーに適用し、マスクを削除します。 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Bradley の適応的閾値アルゴリズム（積分画像閾値）を使用した画像の二値化 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Bradley の適応的閾値アルゴリズム（積分画像閾値）を使用した画像の二値化 |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | 事前定義されたしきい値を使用した画像の二値化 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Otsuしきい値処理による画像の二値化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | データをキャッシュし、基になる [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) から追加のデータ読み込みが行われないことを保証します。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | 画像のトリミング。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | シフト付きで画像をトリミングします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 現在の画像にディザ処理を実行します。 |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 現在の画像にディザ処理を実行します。 |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | レイヤー上に画像を描画します。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 指定された矩形をフィルタリングします。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトオプションを取得します。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | デフォルトの生データ配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。 |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | リソース画像が最後に変更された日時を取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づくオプションを取得します。これにより、元画像のビット深度やその他のパラメータを変更せずに保持できます。例えば、1 ビット/ピクセルの白黒 PNG 画像を読み込み、[`Save`](../../aspose.psd/datastreamsupporter/save/) メソッドで保存すると、8 ビット/ピクセルの PNG 画像が出力されます。これを回避し、1 ビット/ピクセルの PNG 画像として保存するには、このメソッドで対応する保存オプションを取得し、[`Save`](../../aspose.psd/image/save/) メソッドの第2パラメータとして渡します。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 画像のピクセルを取得します。パフォーマンス警告: すべての画像ピクセルを反復処理するためにこのメソッドを使用すると、重大なパフォーマンス問題が発生する可能性があります。より効率的なピクセル操作のためには、`LoadArgb32Pixels` メソッドを使用してピクセル配列全体を一度に取得してください。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 傾き角度を取得します。このメソッドはスキャンされたテキスト文書に適用でき、スキャン時の傾き角度を判定します。 |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | 画像をグレースケール表現に変換する |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32ビット ARGB ピクセルを読み込みます。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64ビット ARGB ピクセルを読み込みます。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK 形式のピクセルを読み込みます。 |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK 形式のピクセルを読み込みます。このメソッドは非推奨です。より効果的な [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) メソッドを使用してください。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32ビット ARGB ピクセルをパック単位で部分的に読み込みます。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | ピクセルをパック単位で部分的に読み込みます。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | ピクセルを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | レイヤーを指定されたレイヤーにマージします。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 角度を正規化します。このメソッドはスキャンされたテキスト文書の歪みを除去するために適用できます。このメソッドは [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) と [`Rotate`](../../aspose.psd/rasterimage/rotate/) メソッドを使用します。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 角度を正規化します。このメソッドはスキャンされたテキスト文書の歪みを除去するために適用できます。このメソッドは [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) と [`Rotate`](../../aspose.psd/rasterimage/rotate/) メソッドを使用します。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 指定されたスキャンラインインデックスでスキャンライン全体を読み取ります。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 指定されたスキャンラインインデックスでスキャンライン全体を読み取ります。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 許容差を持たせてある色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | 許容差を持たせてある色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明度のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明度のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトの NearestNeighbourResample が使用されます。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 高さを比例的にリサイズします。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例的にリサイズします。デフォルトの NearestNeighbourResample が使用されます。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 幅を比例的にリサイズします。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 幅を比例的にリサイズします。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | 画像を中心を基準に回転させます。 |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | 画像を中心を基準に回転させます。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 画像を回転、フリップ、または回転とフリップを行います。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32ビット ARGB ピクセルを保存します。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | ピクセルを保存します。 |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | ピクセルを保存します。このメソッドは非推奨です。より効果的な[`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/)メソッドを使用してください。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | ピクセルを保存します。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 生データを保存します。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 指定された位置に画像の 32 ビット ARGB ピクセルを設定します。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 画像のパレットを設定します。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 指定された位置に画像ピクセルを設定します。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | この[`RasterImage`](../../aspose.psd/rasterimage/)の解像度を設定します。 |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | 現在のレイヤーの浅いコピーを作成します。説明については[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx)をご覧ください。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | ラスタ画像をビットマップに変換します。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |

### 関連項目

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


