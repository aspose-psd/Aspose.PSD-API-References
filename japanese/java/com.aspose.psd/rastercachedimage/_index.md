---
title: "RasterCachedImage"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ラスター グラフィックス操作をサポートするラスター画像を表します。"
type: docs
weight: 85
url: /ja/java/com.aspose.psd/rastercachedimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

ラスターグラフィック操作をサポートするラスター画像を表します。この画像は必要に応じてピクセルデータをキャッシュします。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | 画像が読み込まれたときに発生します |
| [OnLoad_internalized](#OnLoad-internalized) | 画像が createFirstSupportedLoader によって読み込まれたときに発生します |
| [OnSave_internalized](#OnSave-internalized) | 画像が読み込まれたまたは保存されたときに発生します |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | クレジットが使用されたときに発生します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 画像の明るさを調整します。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 画像のコントラスト調整 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 画像のガンマ補正です。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 画像のガンマ補正です。 |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | リサイズ処理を開始します。 |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | 積分画像しきい値を使用したブレイドリーの適応的しきい値アルゴリズムで画像を二値化します |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 積分画像しきい値を使用したブレイドリーの適応的しきい値アルゴリズムで画像を二値化します |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 事前定義されたしきい値で画像を二値化します |
| [binarizeOtsu()](#binarizeOtsu--) | 大津しきい値で画像を二値化します |
| [cacheData()](#cacheData--) | データをキャッシュし、基礎となる DataStreamSupporter.DataStreamContainer から追加のデータ読み込みが行われないことを保証します。 |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | 指定されたストリームから画像を読み込めるかどうかを判断します。 |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | 指定されたストリームから画像を読み込めるかどうか、オプションで指定された loadOptions を使用して判断します。 |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | 指定されたファイルパスから画像をロードできるかどうかを判定します。 |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | 指定されたファイルパスから画像をロードできるか、また必要に応じて指定されたオープンオプションを使用できるかどうかを判定します。 |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps に変換します。 |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | 指定された作成オプションを使用して新しい画像を作成します。 |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | 指定された画像をページとして使用して新しい画像を作成します |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | 指定された画像をページとして新しい画像を作成します。 |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | 画像をトリミングします。 |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | シフト付きで画像をトリミングします。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | 現在の画像にディザリングを実行します。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | 現在の画像にディザリングを実行します。 |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | 画像をトリミングします。 |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | 画像のサイズを変更します。 |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | 画像を回転、フリップ、または回転とフリップを行います。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | 指定された矩形をフィルタリングします。 |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | 自動調整パレットかどうかを示す値を取得します。 |
| [getBackgroundColor()](#getBackgroundColor--) | 背景色の値を取得または設定します。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 画像のピクセルあたりのビット数を取得します。 |
| [getBounds()](#getBounds--) | 画像の境界を取得します。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 内部バッファ全体に対して定義された最大許容サイズであるバッファサイズのヒントを取得します。 |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Image コンテナを取得します。 |
| [getDataStreamContainer()](#getDataStreamContainer--) | オブジェクトのデータストリームを取得します。 |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | 深く調整されたパレットを取得します。 |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | デフォルトオプションを取得します。 |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | 部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。 |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | 部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。 |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | デフォルトの生データ配列を取得します。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getFileFormat()](#getFileFormat--) | ファイル形式の値を取得します。 |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | ファイル形式を取得します。 |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | ファイル形式を取得します。 |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | ファイル形式を取得します。 |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | 現在の画像に合わせた矩形を取得します。 |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | 現在の画像に合わせた矩形を取得します。 |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | フォーマット固有の場所からパレットを取得します。 |
| [getHeight()](#getHeight--) | 画像の高さを取得します。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | この  RasterImage の水平解像度（インチあたりピクセル数）を取得または設定します。 |
| [getImageOpacity()](#getImageOpacity--) | この画像の不透明度を取得します。 |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | 内部データトランスフォーマーを取得します。 |
| [getInterruptMonitor()](#getInterruptMonitor--) | 割り込みモニターを取得します。 |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | 部分回転保存のために許可される最大割り当てを取得または設定します。 |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | メモリマネージャーを取得します。 |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | リソース画像が最後に変更された日時を取得します。 |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | 元のファイル設定に基づくオプションを取得します。 |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | 描画可能な画像を取得します。 |
| [getPalette()](#getPalette--) | カラーパレットを取得します。 |
| [getPixel(int x, int y)](#getPixel-int-int-) | 画像ピクセルを取得します。 |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | 画像コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。 |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | プライベートフォントキャッシュを作成します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 進行状況イベントハンドラ情報を取得します。 |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | 進行状況イベントハンドラ情報を取得します。 |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | 比例高さを取得します。 |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | 比例幅を取得します。 |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | カスタムカラーコンバータを取得または設定します |
| [getRawDataFormat()](#getRawDataFormat--) | 生データ形式を取得します。 |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | インデックスカラーコンバータを取得または設定します |
| [getRawLineSize()](#getRawLineSize--) | 生ラインサイズ（バイト単位）を取得します。 |
| [getRotateMode()](#getRotateMode--) | 回転モードを取得または設定します。 |
| [getSize()](#getSize--) | 画像サイズを取得します。 |
| [getSkewAngle()](#getSkewAngle--) | 傾き角度を取得します。 |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | ソース画像が存在する場合、そのファイルパスを取得します。 |
| [getTransparentColor()](#getTransparentColor--) | 画像の透過色を取得します。 |
| [getUpdateXmpData()](#getUpdateXmpData--) | XMP メタデータを更新するかどうかを示す値を取得または設定します。 |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | オブジェクトがメモリ最適化戦略を使用するかどうかを示す値を取得します |
| [getUseRawData()](#getUseRawData--) | 生データロードが利用可能な場合に生データロードを使用するかどうかを示す値を取得または設定します。 |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | 使用されているパレットを取得します。 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | ベンチャーライセンスを取得します。 |
| [getVerticalResolution()](#getVerticalResolution--) | この RasterImage の垂直解像度（インチあたりピクセル数）を取得または設定します。 |
| [getWidth()](#getWidth--) | 画像の幅を取得します。 |
| [getXmpData()](#getXmpData--) | XMP メタデータを取得または設定します。 |
| [grayscale()](#grayscale--) | 画像をグレースケール表現に変換する |
| [hasAlpha()](#hasAlpha--) | このインスタンスにアルファがあるかどうかを示す値を取得します。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 画像に背景色があるかどうかを示す値を取得します。 |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | 画像のこのインスタンスがロード後に変更されたかどうかを示す値を取得または設定します。 |
| [hasTransparentColor()](#hasTransparentColor--) | 画像に透過色があるかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | 進捗の最大値を取得または設定します |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 進捗を示します。 |
| [isCached()](#isCached--) | 画像データが現在キャッシュされているかどうかを示す値を取得します。 |
| [isRawDataAvailable()](#isRawDataAvailable--) | 生データロードが利用可能かどうかを示す値を取得します。 |
| [isUsePalette()](#isUsePalette--) | 画像パレットが使用されているかどうかを示す値を取得します。 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 指定されたストリームから新しい画像をロードします。 |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | 指定されたストリームから新しい画像をロードします。 |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | 指定されたストリームから新しい画像をロードします。 |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | 指定されたストリームから新しい画像をロードします。 |
| [load(String filePath)](#load-java.lang.String-) | 指定されたファイルから新しい画像をロードします。 |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | 指定されたファイルから新しい画像をロードします。 |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | 32ビット ARGB ピクセルをロードします。 |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | 64ビット ARGB ピクセルをロードします。 |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | CMYK 形式のピクセルをロードします。 |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | CMYK 形式のピクセルをロードします。 |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | パック単位で 32 ビット ARGB ピクセルを部分的にロードします。 |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | パック単位でピクセルを部分的にロードします。 |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | ピクセルをロードします。 |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 部分処理メカニズムを使用して生画像データをロードします。 |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 生データをロードします。 |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | 指定されたストリームから新しい画像をロードします。 |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | 指定されたストリームから新しい画像をロードします。 |
| [normalizeAngle()](#normalizeAngle--) | 角度を正規化します。 |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | 角度を正規化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | この[Image](../../com.aspose.psd/image)のコンテナが設定されたときに呼び出します。 |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | 指定されたスキャンラインインデックスで全スキャンラインを読み取ります。 |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | 指定されたスキャンラインインデックスで全スキャンラインを読み取ります。 |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | 許容差である色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | 許容差である色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | 画像のサイズを変更します。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | 画像のサイズを変更します。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 画像のサイズを変更します。 |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | 高さを比例的にリサイズします。 |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | 高さを比例的にリサイズします。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 高さを比例的にリサイズします。 |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | 幅を比例的にリサイズします。 |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | 幅を比例的にリサイズします。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 幅を比例的にリサイズします。 |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | 指定された逆スケールでレイヤーのサイズを変更します。 |
| [rotate(float angle)](#rotate-float-) | 画像を中心の周りに回転させます。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | 画像を中心の周りに回転させます。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | 画像データを基になるストリームに保存します。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | オブジェクトのデータを指定されたストリームに保存します。 |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | 画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。 |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。 |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | オブジェクトのデータを指定されたストリームに保存します。 |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で指定されたファイル場所に保存します。 |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。 |
| [save(String filePath)](#save-java.lang.String-) | オブジェクトのデータを指定されたファイル場所に保存します。 |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | オブジェクトのデータを指定されたファイル場所に保存します。 |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で指定されたファイル場所に保存します。 |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で指定されたファイル場所に保存します。 |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | 32ビット ARGB ピクセルを保存します。 |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | ピクセルを保存します。 |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | ピクセルを保存します。 |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | ピクセルを保存します。 |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | 生データを保存します。 |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。 |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | 指定された位置に画像の 32ビット ARGB ピクセルを設定します。 |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | 自動パレット調整を行うかどうかを示す値を設定します。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 背景色の値を取得または設定します。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | すべての内部バッファに対して許容される最大サイズとして定義されたバッファサイズヒントを設定します。 |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Image コンテナを設定します。 |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | データローダーを直接設定します。 |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | オブジェクトのデータストリームを設定します。 |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | フォーマット固有の場所にパレットを設定します |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | この  RasterImage の水平解像度（インチあたりピクセル数）を取得または設定します。 |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 保存後に [ignore after save] かどうかを示す値を設定します。 |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | 画像のこのインスタンスがロード後に変更されたかどうかを示す値を取得または設定します。 |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | 内部データトランスフォーマーを設定します。 |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | 割り込みモニターを設定します。 |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | 部分回転保存のために許可される最大割り当てを取得または設定します。 |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | メモリマネージャーを設定します。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | カラーパレットを設定します。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | 画像パレットを設定します。 |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | 指定された位置の画像ピクセルを設定します。 |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 画像コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。 |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | カスタムカラーコンバータを取得または設定します |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | インデックスカラーコンバータを取得または設定します |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | この RasterImage の解像度を設定します。 |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | 回転モードを取得または設定します。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 画像に透過色があるかどうかを示す値を取得します。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | 画像の透過色を取得します。 |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | XMP メタデータを更新するかどうかを示す値を取得または設定します。 |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | 生データロードが利用可能な場合に生データロードを使用するかどうかを示す値を取得または設定します。 |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | すべての Aspose 製品はこのメソッドを実装すべきです。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | この RasterImage の垂直解像度（インチあたりピクセル数）を取得または設定します。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP メタデータを取得または設定します。 |
| [toBitmap()](#toBitmap--) | ラスタ画像をビットマップに変換します。 |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |
### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


画像が読み込まれたときに発生します

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


画像が createFirstSupportedLoader によって読み込まれたときに発生します

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


画像が読み込まれたまたは保存されたときに発生します

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


クレジットが使用されたときに発生します

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


画像の明るさを調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brightness | int | 明るさの値です。 |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


画像のコントラスト調整

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| contrast | float | コントラストの値（範囲 [-100; 100]） |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


画像のガンマ補正です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| gamma | float | 赤、緑、青チャンネルのガンマ係数 |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


画像のガンマ補正です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| gammaRed | float | 赤チャンネル係数のガンマ |
| gammaGreen | float | 緑チャンネル係数のガンマ |
| gammaBlue | float | 青チャンネル係数のガンマ |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


リサイズ処理を開始します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい画像の幅です。 |
| newHeight | int | 新しい画像の高さです。 |

**Returns:**
com.aspose.internal.IResizeController - リサイズコントローラです。
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


積分画像しきい値を使用したブレイドリーの適応的しきい値アルゴリズムで画像を二値化します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brightnessDifference | double | このピクセルを中心とした s x s ウィンドウ内のピクセルの平均とピクセルとの明るさの差です。 |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


積分画像しきい値を使用したブレイドリーの適応的しきい値アルゴリズムで画像を二値化します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brightnessDifference | double | このピクセルを中心とした s x s ウィンドウ内のピクセルの平均とピクセルとの明るさの差です。 |
| windowSize | int | このピクセルを中心とした s x s ウィンドウのサイズです。 |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


事前定義されたしきい値で画像を二値化します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threshold | byte | しきい値。ピクセルの対応するグレイ値がしきい値より大きい場合、255 の値が割り当てられ、そうでなければ 0 が割り当てられます。 |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


大津しきい値で画像を二値化します

### cacheData() {#cacheData--}
```
public void cacheData()
```


データをキャッシュし、基礎となる DataStreamSupporter.DataStreamContainer から追加のデータ読み込みが行われないことを保証します。

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


指定されたストリームから画像を読み込めるかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 読み込み元のストリームです。 |

**Returns:**
boolean -  true  画像を指定されたストリームから読み込める場合は true、そうでない場合は false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


指定されたストリームから画像を読み込めるかどうか、オプションで指定された loadOptions を使用して判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 読み込み元のストリームです。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

**Returns:**
boolean -  true  画像を指定されたストリームから読み込める場合は true、そうでない場合は false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


指定されたファイルパスから画像をロードできるかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイルパスです。 |

**Returns:**
boolean -  true  が、指定されたファイルから画像をロードできる場合; それ以外の場合は  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


指定されたファイルパスから画像をロードできるか、また必要に応じて指定されたオープンオプションを使用できるかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイルパスです。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

**Returns:**
boolean -  true  が、指定されたファイルから画像をロードできる場合; それ以外の場合は  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 使用する保存オプション。 |

**Returns:**
boolean -  true  が、渡された保存オプションで表される指定されたファイル形式に画像を保存できる場合; それ以外の場合は  false .
### close() {#close--}
```
public void close()
```


Closable インターフェイスを実装し、JDK 1.7 以降の try-with-resources 文で使用できます。このメソッドは単に dispose メソッドを呼び出すだけです。

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


aps に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプション。 |
| モード | int | モード。 |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | クリッピング矩形。 |

**Returns:**
com.aspose.foundation.rendering.ApsPage - APS ページ。
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


指定された作成オプションを使用して新しい画像を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 画像オプション。 |
| 幅 | int | 幅。 |
| 高さ | int | 高さ。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


指定された画像をページとして使用して新しい画像を作成します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | 画像。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


指定された画像をページとして新しい画像を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | 画像。 |
| disposeImages | boolean | true に設定すると、[dispose images]。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| 幅 | int |  |
| 高さ | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


画像をトリミングします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 矩形です。 |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


シフト付きで画像をトリミングします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| leftShift | int | 左シフトです。 |
| rightShift | int | 右シフトです。 |
| topShift | int | 上シフトです。 |
| bottomShift | int | 下シフトです。 |

### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


現在の画像にディザリングを実行します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ditheringMethod | int | ディザリング方式です。 |
| bitsCount | int | ディザリングの最終ビット数です。 |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


現在の画像にディザリングを実行します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ditheringMethod | int | ディザリング方式です。 |
| bitsCount | int | ディザリングの最終ビット数です。 |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | ディザリング用のカスタムパレットです。 |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


画像をトリミングします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 矩形です。 |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


画像のサイズを変更します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい幅です。 |
| newHeight | int | 新しい高さです。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | リサイズ設定です。 |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float |  |
| 比例的にリサイズ | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


画像を回転、フリップ、または回転とフリップを行います。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 回転フリップタイプ | int | 回転フリップタイプです。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


指定された矩形をフィルタリングします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 矩形です。 |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | オプション。 |

### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


画像の 32 ビット ARGB ピクセルを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | ピクセル x の位置です。 |
| y | int | ピクセル y の位置です。 |

**Returns:**
int - 指定された位置の 32 ビット ARGB ピクセルです。
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


自動調整パレットかどうかを示す値を取得します。

**Returns:**
boolean - 自動調整パレットを有効にする場合は true、そうでない場合は false。
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


背景色の値を取得または設定します。

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


画像のピクセルあたりのビット数を取得します。

**Returns:**
int - 画像のピクセルあたりビット数。
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


画像の境界を取得します。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


内部バッファ全体に対して定義された最大許容サイズであるバッファサイズのヒントを取得します。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Returns:**
int - バッファサイズのヒントで、すべての内部バッファに対して定義された最大許容サイズです。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Image コンテナを取得します。

値: Image コンテナです。

このプロパティが null でない場合、画像が別の画像内に含まれていることを示します。

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


オブジェクトのデータストリームを取得します。

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


深く調整されたパレットを取得します。

**Returns:**
boolean - 深く調整されたパレットです。
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


デフォルトの 32 ビット ARGB ピクセル配列を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを取得する矩形です。 |

**Returns:**
int[] - デフォルトのピクセル配列です。
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


デフォルトオプションを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| args | java.lang.Object[] | 引数です。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを取得する矩形です。 |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 部分的なピクセルローダーです。 |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを取得する矩形です。 |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 部分的な生データローダーです。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 生データ設定です。 |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


デフォルトの生データ配列を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 生データを取得する矩形です。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 生データ設定です。 |

**Returns:**
byte[] - デフォルトの生データ配列です。
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


ファイル形式の値を取得します。

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


ファイル形式を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | ストリーム。 |

--------------------

決定されたファイル形式は、指定された画像が読み込めることを意味しません。CanLoad メソッドのオーバーロードのいずれかを使用して、ストリームが読み込めるかどうかを判断してください。 |

**Returns:**
long - 決定されたファイル形式。
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


ファイル形式を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | stream | java.io.InputStream | ストリーム。 |

決定されたファイル形式は、指定された画像が読み込めることを意味しません。CanLoad メソッドのオーバーロードのいずれかを使用して、ストリームが読み込めるかどうかを判断してください。 |

**Returns:**
long - 決定されたファイル形式。
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


ファイル形式を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ファイルパスです。 |

決定されたファイル形式は、指定された画像が読み込めることを意味しません。CanLoad メソッドのオーバーロードのいずれかを使用して、ファイルが読み込めるかどうかを判断してください。 |

**Returns:**
long - 決定されたファイル形式。
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


現在の画像に合わせた矩形を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 適合矩形を取得するための矩形。 |
| 幅 | int | オブジェクトの幅。 |
| 高さ | int | オブジェクトの高さ。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


現在の画像に合わせた矩形を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 適合矩形を取得するための矩形。 |
| ピクセル | int[] | 32ビット ARGB ピクセル。 |
| 幅 | int | オブジェクトの幅。 |
| 高さ | int | オブジェクトの高さ。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


フォーマット固有の場所からパレットを取得します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


画像の高さを取得します。

**Returns:**
int - 画像の高さ。
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


この  RasterImage の水平解像度（インチあたりピクセル数）を取得または設定します。

**Returns:**
double - 水平解像度。

注: デフォルトではこの値は常に 96 です。異なるプラットフォームでは画面解像度を取得できないためです。両方の解像度値を一度の呼び出しで更新するには SetResolution メソッドの使用を検討してください。
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


この画像の不透明度を取得します。

**Returns:**
float - 0.0（完全に透明）から 1.0（完全に不透明）までの不透明度の値。
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


内部データトランスフォーマーを取得します。

値: 内部データ変換器。

**Returns:**
com.aspose.internal.IInnerDataTransformer - 内部データ変換器。
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


割り込みモニターを取得します。

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


部分回転保存のために許可される最大割り当てを取得または設定します。

**Returns:**
int - 部分回転保存に許可される最大割り当て量。
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


メモリマネージャーを取得します。

値: メモリマネージャー。

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - メモリマネージャー。
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


リソース画像が最後に変更された日時を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| useDefault | boolean | true に設定すると、FileInfo の情報をデフォルト値として使用します。 |

**Returns:**
java.util.Date - リソース画像が最後に変更された日時。
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


元のファイル設定に基づくオプションを取得します。これにより、元画像のビット深度やその他のパラメータを変更せずに保持できます。例えば、1 ビット/ピクセルの白黒 PNG 画像を読み込み、`DataStreamSupporter.Save(string)` メソッドで保存すると、8 ビット/ピクセルの PNG 画像が出力されます。これを回避し、1 ビット/ピクセルの PNG 画像として保存するには、このメソッドで対応する保存オプションを取得し、第二パラメータとして `Image.Save(string, ImageOptionsBase)` メソッドに渡します。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


描画可能な画像を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


カラー パレットを取得します。ピクセルが直接表現されている場合、カラー パレットは使用されません。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


画像ピクセルを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | ピクセル x の位置です。 |
| y | int | ピクセル y の位置です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


画像コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。

**Returns:**
boolean -  true  画像コンポーネントが事前乗算される必要がある場合; それ以外の場合は  false 。
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


プライベートフォントキャッシュを作成します。

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - プライベート フォント キャッシュです。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


進行状況イベントハンドラ情報を取得します。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


進行状況イベントハンドラ情報を取得します。

Value: 進捗イベント ハンドラ情報です。

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


比例高さを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 | int | 幅。 |
| 高さ | int | 高さ。 |
| newWidth | int | 新しい幅です。 |

**Returns:**
int - 比例高さです。
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


比例幅を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 | int | 幅。 |
| 高さ | int | 高さ。 |
| newHeight | int | 新しい高さです。 |

**Returns:**
int - 比例幅です。
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


カスタムカラーコンバータを取得または設定します

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


生データ形式を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


現在の生データ設定を取得します。これらの設定を使用すると、データは変換なしでロードされることに注意してください。

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します

**Returns:**
int - パレットインデックスが範囲外の場合に使用するフォールバック インデックスです
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


インデックスカラーコンバータを取得または設定します

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


生ラインサイズ（バイト単位）を取得します。

**Returns:**
int - 生ラインのサイズ（バイト単位）です。
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


回転モードを取得または設定します。

**Returns:**
int - 回転モードです。
### getSize() {#getSize--}
```
public Size getSize()
```


画像サイズを取得します。

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


傾き角度を取得します。このメソッドはスキャンされたテキスト文書に適用でき、スキャン時の傾き角度を決定します。

**Returns:**
float - 傾き角度（度単位）です。
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


ソース画像が存在する場合、そのファイルパスを取得します。ソースパスが見つからない場合は空文字列を返します。

**Returns:**
java.lang.String - ソース画像のファイルパスです。
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


画像の透過色を取得します。

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


XMP メタデータを更新するかどうかを示す値を取得または設定します。

**Returns:**
boolean -  true  XMP メタデータを更新する場合; それ以外の場合は  false 。
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


オブジェクトがメモリ最適化戦略を使用するかどうかを示す値を取得します

Value:  true  オブジェクトがメモリ最適化戦略を使用する場合; それ以外の場合は  false 。

**Returns:**
boolean - オブジェクトがメモリ最適化戦略を使用するかどうかを示す値です
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


生データロードが利用可能な場合に生データロードを使用するかどうかを示す値を取得または設定します。

**Returns:**
boolean -  true  生データロードが利用可能な場合に生データロードを使用する場合; それ以外の場合は  false 。
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


使用されているパレットを取得します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


ベンチャーライセンスを取得します。

**Returns:**
java.lang.Object - ベンチャー ライセンスをオブジェクトとして表します。
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


この RasterImage の垂直解像度（インチあたりピクセル数）を取得または設定します。

**Returns:**
double - 垂直解像度。

注: デフォルトではこの値は常に 96 です。異なるプラットフォームでは画面解像度を取得できないためです。両方の解像度値を一度の呼び出しで更新するには SetResolution メソッドの使用を検討してください。
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


画像の幅を取得します。

**Returns:**
int - 画像の幅。
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP メタデータを取得または設定します。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


画像をグレースケール表現に変換する

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


このインスタンスにアルファがあるかどうかを示す値を取得します。

**Returns:**
boolean - このインスタンスがアルファを持つ場合は true、そうでない場合は false。
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


画像に背景色があるかどうかを示す値を取得します。

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


画像のこのインスタンスがロード後に変更されたかどうかを示す値を取得または設定します。

**Returns:**
boolean -  true  このインスタンスの画像が変更された場合; それ以外の場合は  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


画像に透過色があるかどうかを示す値を取得します。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


進捗の最大値を取得または設定します

Value: 進捗の最大値

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


進捗を示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


画像データが現在キャッシュされているかどうかを示す値を取得します。

**Returns:**
boolean -  true  画像データがキャッシュされている場合; それ以外の場合は  false .
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


生データロードが利用可能かどうかを示す値を取得します。

**Returns:**
boolean -  true  この生データの読み込みが利用可能な場合; それ以外の場合は  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


画像パレットが使用されているかどうかを示す値を取得します。

Value:  true  画像でパレットが使用されている場合; それ以外の場合は  false .

**Returns:**
boolean - 画像パレットが使用されているかを示す値。
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


指定されたストリームから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 画像を読み込むストリーム。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


指定されたストリームから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 画像を読み込むストリーム。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


指定されたストリームから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル | java.io.RandomAccessFile | 画像を読み込むファイル。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


指定されたストリームから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル | java.io.RandomAccessFile | 画像を読み込むファイル。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


指定されたファイルから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 画像を読み込むファイルパス。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


指定されたファイルから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 画像を読み込むファイルパス。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


32ビット ARGB ピクセルをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns:**
int[] - 読み込まれた 32 ビット ARGB ピクセル配列。
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


64ビット ARGB ピクセルをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns:**
long[] - 読み込まれた 64 ビット ARGB ピクセル配列。
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


CMYK 形式のピクセルをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns:**
int[] - 読み込まれた CMYK ピクセルが 32 ビット整数値として表される。
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


CMYK 形式でピクセルを読み込みます。このメソッドは非推奨です。より効果的な loadCmyk32Pixels(Rectangle) メソッドを使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns:**
com.aspose.psd.CmykColor[] - 読み込まれた CMYK ピクセル配列。
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


パック単位で 32 ビット ARGB ピクセルを部分的にロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目的の矩形。 |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 32 ビット ARGB ピクセルローダー。 |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


パック単位でピクセルを部分的にロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目的の矩形。 |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | ピクセルローダー。 |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


ピクセルをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns:**
com.aspose.psd.Color[] - 読み込まれたピクセル配列です。
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


部分処理メカニズムを使用して生画像データをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | データを読み込む画像の目的の矩形領域。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 生データ設定です。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 生データローダー。 |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


生データをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 生データを読み込む矩形。 |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | 宛先画像の境界。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 読み込まれたデータに使用する生データ設定です。指定された形式でない場合はデータ変換が実行されますのでご注意ください。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 生データローダー。 |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


指定されたストリームから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 画像を読み込むストリーム。 |
| startPosition | long | 画像を読み込む開始位置。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


指定されたストリームから新しい画像をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 画像を読み込むストリーム。 |
| startPosition | long | 画像を読み込む開始位置。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


角度を正規化します。このメソッドはスキャンされたテキスト文書の歪みを除去するために適用できます。このメソッドは [.getSkewAngle](../../null/\#getSkewAngle) と [.rotate(float)](../../null/\#rotate-float-) メソッドを使用します。

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


角度を正規化します。このメソッドはスキャンされたテキスト文書の歪みを除去するために適用できます。このメソッドは [.getSkewAngle](../../null/\#getSkewAngle) と [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) メソッドを使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 比例的にリサイズ | boolean | true に設定すると、回転した矩形（コーナーポイント）の投影に従って画像サイズが変更されます。設定しない場合はサイズはそのままで、内部の画像内容のみが回転します。 |
| backgroundColor | [Color](../../com.aspose.psd/color) | 背景色。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


この[Image](../../com.aspose.psd/image)のコンテナが設定されたときに呼び出します。

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


指定されたスキャンラインインデックスで全スキャンラインを読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scanLineIndex | int | スキャンラインのゼロベースインデックス。 |

**Returns:**
int[] - スキャンラインの 32 ビット ARGB カラー値配列です。
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


指定されたスキャンラインインデックスで全スキャンラインを読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scanLineIndex | int | スキャンラインのゼロベースインデックス。 |

**Returns:**
com.aspose.psd.Color[] - スキャンラインのピクセルカラー値配列です。
### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


許容差である色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | 置き換えられる元の色。 |
| oldColorDiff | byte | 置き換えられた色調を広げるために許容される元の色の差分。 |
| newColor | [Color](../../com.aspose.psd/color) | 元の色を置き換える新しい色。 |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


許容差である色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| oldColorArgb | int | 置き換えられる古い色の ARGB 値。 |
| oldColorDiff | byte | 置き換えられた色調を広げるために許容される元の色の差分。 |
| newColorArgb | int | 古い色と置き換えるための新しい色の ARGB 値。 |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明性のない画像に使用すると、すべての色が単一の色に置き換えられます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | 非透明色を置き換えるための新しい色。 |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明性のない画像に使用すると、すべての色が単一の色に置き換えられます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorArgb | int | 非透明色を置き換えるための新しい色の ARGB 値。 |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


画像のサイズを変更します。デフォルトの ResizeType.LeftTopToLeftTop が使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい幅です。 |
| newHeight | int | 新しい高さです。 |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


画像のサイズを変更します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい幅です。 |
| newHeight | int | 新しい高さです。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | リサイズ設定です。 |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


画像のサイズを変更します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい幅です。 |
| newHeight | int | 新しい高さです。 |
| resizeType | int | リサイズの種類。 |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


高さを比例的にリサイズします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newHeight | int | 新しい高さです。 |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


高さを比例的にリサイズします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newHeight | int | 新しい高さです。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


高さを比例的にリサイズします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newHeight | int | 新しい高さです。 |
| resizeType | int | リサイズのタイプ。 |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


幅を比例的にリサイズします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい幅です。 |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


幅を比例的にリサイズします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい幅です。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


幅を比例的にリサイズします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | int | 新しい幅です。 |
| resizeType | int | リサイズのタイプ。 |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


指定された逆スケールでレイヤーのサイズを変更します。（新しい幅 = 元の幅 / スケール；新しい高さ = 元の高さ / スケール）

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | double | X スケール。 |
| scaleY | double | Y スケール。 |
| resizeType | int | リサイズのタイプ。 |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


画像を中心の周りに回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度（度単位）。正の値は時計回りに回転します。 |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


画像を中心の周りに回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度（度単位）。正の値は時計回りに回転します。 |
| 比例的にリサイズ | boolean | true に設定すると、回転した矩形（コーナーポイント）の投影に従って画像サイズが変更されます。設定しない場合はサイズはそのままで、内部の画像内容のみが回転します。 |
| backgroundColor | [Color](../../com.aspose.psd/color) | 背景色。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


画像を回転、フリップ、または回転とフリップを行います。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 回転フリップタイプ | int |  |

### save() {#save--}
```
public final void save()
```


画像データを基になるストリームに保存します。

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | オブジェクトのデータを保存するストリーム。 |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 画像のデータを保存するストリーム。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存オプション。 |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 画像のデータを保存するストリーム。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存オプション。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 宛先画像の境界矩形。ソース境界を使用する場合は空の矩形を設定します。 |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル | java.io.RandomAccessFile | オブジェクトのデータを保存するストリーム。 |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


オブジェクトのデータを、保存オプションに従って指定されたファイル形式で指定されたファイル場所に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル | java.io.RandomAccessFile | 画像のデータを保存するファイル。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプション。 |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル | java.io.RandomAccessFile | 画像のデータを保存するファイル。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存オプション。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 対象画像の境界矩形。空の矩形を設定するとソースの境界が使用されます。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


オブジェクトのデータを指定されたファイル場所に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | オブジェクトのデータを保存するためのファイルパス。 |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


オブジェクトのデータを指定されたファイル場所に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | オブジェクトのデータを保存するためのファイルパス。 |
| overWrite | boolean | true に設定するとファイル内容を上書きし、そうでなければ追記されます。 |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


オブジェクトのデータを、保存オプションに従って指定されたファイル形式で指定されたファイル場所に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイルパスです。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプション。 |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


オブジェクトのデータを、保存オプションに従って指定されたファイル形式で指定されたファイル場所に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイルパスです。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプション。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 対象画像の境界矩形。空の矩形を設定するとソースの境界が使用されます。 |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


32ビット ARGB ピクセルを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを保存するための矩形。 |
| ピクセル | int[] | 32 ビット ARGB ピクセル配列。 |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


ピクセルを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを保存するための矩形。 |
| ピクセル | int[] | 32 ビット整数値として表現された CMYK ピクセル。 |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


ピクセルを保存します。このメソッドは非推奨です。より効果的な saveCmyk32Pixels(Rectangle, int[]) メソッドを使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを保存するための矩形。 |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK ピクセル配列。 |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


ピクセルを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを保存するための矩形。 |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ピクセル配列。 |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


生データを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | 生データ。 |
| dataOffset | int | 開始生データオフセット。 |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 生データの矩形。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | データが存在する生データの設定。 |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


画像のデータを、保存オプションに従って指定されたファイル形式で指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 画像のデータを保存するストリーム。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存オプション。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 宛先画像の境界矩形。ソース境界を使用する場合は空の矩形を設定します。 |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


指定された位置に画像の 32ビット ARGB ピクセルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | ピクセル x の位置です。 |
| y | int | ピクセル y の位置です。 |
| argb32Color | int | 指定位置の 32 ビット ARGB ピクセル。 |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


自動パレット調整を行うかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 自動パレット調整を有効にする場合は true、そうでない場合は false。 |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


画像に背景色があるかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


背景色の値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


すべての内部バッファに対して許容される最大サイズとして定義されたバッファサイズヒントを設定します。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズのヒント。 |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Image コンテナを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Image コンテナ。 |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


データローダーを直接設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | データローダー。 |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


オブジェクトのデータストリームを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | オブジェクトのデータストリーム。 |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


フォーマット固有の場所にパレットを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 新しい 32 ビット ARGB パレット。 |

**Returns:**
boolean
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


この  RasterImage の水平解像度（インチあたりピクセル数）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | double | 水平解像度。 |

注: デフォルトではこの値は常に96です。異なるプラットフォームでは画面解像度を取得できないためです。単一呼び出しで両方の解像度値を更新するには SetResolution メソッドの使用を検討してください。 |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


保存後に [ignore after save] かどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | true  の場合は [ignore after save]; それ以外は false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


画像のこのインスタンスがロード後に変更されたかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | true  の場合はこのインスタンスの画像が変更されたことを示します; それ以外は false . |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


内部データトランスフォーマーを設定します。

値: 内部データ変換器。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.IInnerDataTransformer | 内部データトランスフォーマー。 |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


割り込みモニターを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | 割り込みモニター。 |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


部分回転保存のために許可される最大割り当てを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 部分回転保存に対して許可される最大割り当て量。 |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


メモリマネージャーを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | メモリマネージャ。 |
| needDispose | boolean | true に設定された場合は [need dispose]。 |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


カラーパレットを設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


画像パレットを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 設定するパレット。 |
| updateColors | boolean | true に設定された場合、色は新しいパレットに従って更新されます。そうでない場合、カラーインデックスは変更されません。インデックスが変更されないと、対応するパレットエントリがないインデックスがある場合、画像の読み込み時にクラッシュする可能性があることに注意してください。 |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


指定された位置の画像ピクセルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | ピクセル x の位置です。 |
| y | int | ピクセル y の位置です。 |
| color | [Color](../../com.aspose.psd/color) | 指定された位置のピクセル色。 |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


画像コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | true  の場合は画像コンポーネントが事前乗算される必要があります; それ以外は false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


カスタムカラーコンバータを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | カスタムカラーコンバータ |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | パレットインデックスが範囲外の場合に使用するフォールバックインデックス |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


インデックスカラーコンバータを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | インデックスカラーコンバータ |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


この RasterImage の解像度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dpiX | double | RasterImage の水平解像度（ドット毎インチ）。 |
| dpiY | double | RasterImage の垂直解像度（ドット毎インチ）。 |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


回転モードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 回転モードです。 |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


画像に透過色があるかどうかを示す値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


画像の透過色を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


XMP メタデータを更新するかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | XMP メタデータを更新する場合は true、そうでない場合は false。 |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


生データロードが利用可能な場合に生データロードを使用するかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 生データの読み込みが利用可能な場合に使用する場合は true、そうでない場合は false。 |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


すべての Aspose 製品はこのメソッドを実装すべきです。このメソッドは GroupDocs 製品から呼び出され、GroupDocs 自体がライセンスされているかどうかを示し、カスタム透かしを指定します。GroupDocs がライセンスされている場合、このドキュメント インスタンスも Aspose 製品がライセンスされていなくてもライセンス済みとして動作すべきです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


この RasterImage の垂直解像度（インチあたりピクセル数）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | double | 垂直解像度です。 |

注: デフォルトではこの値は常に96です。異なるプラットフォームでは画面解像度を取得できないためです。単一呼び出しで両方の解像度値を更新するには SetResolution メソッドの使用を検討してください。 |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP メタデータを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP メタデータです。 |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


ラスタ画像をビットマップに変換します。

**Returns:**
java.awt.image.BufferedImage - ビットマップ
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


指定されたスキャンラインインデックスに全スキャンラインを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scanLineIndex | int | スキャンラインのゼロベースインデックス。 |
| argb32Pixels | int[] | 書き込む 32 ビット ARGB カラー配列です。 |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


指定されたスキャンラインインデックスに全スキャンラインを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scanLineIndex | int | スキャンラインのゼロベースインデックス。 |
| pixels | [Color\[\]](../../com.aspose.psd/color) | 書き込むピクセルカラー配列です。 |

