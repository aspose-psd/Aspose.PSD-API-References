---
title: "Image"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Image はすべての画像タイプの基底クラスです。"
type: docs
weight: 54
url: /ja/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

Image はすべての画像タイプの基底クラスです。
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
| [cacheData()](#cacheData--) | データをキャッシュし、基礎となる DataStreamSupporter.DataStreamContainer から追加のデータ読み込みが行われないことを保証します。 |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | 指定されたストリームから画像を読み込めるかどうかを判断します。 |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | 指定されたストリームから画像を読み込めるかどうか、オプションで指定された loadOptions を使用して判断します。 |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | 指定されたファイルパスから画像をロードできるかどうかを判定します。 |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | 指定されたファイルパスから画像をロードできるか、また必要に応じて指定されたオープンオプションを使用できるかどうかを判定します。 |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps に変換します。 |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | 指定された作成オプションを使用して新しい画像を作成します。 |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | 指定された画像をページとして使用して新しい画像を作成します |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | 指定された画像をページとして新しい画像を作成します。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | 自動調整パレットかどうかを示す値を取得します。 |
| [getBackgroundColor()](#getBackgroundColor--) | 背景色の値を取得または設定します。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 画像のピクセルあたりのビット数を取得します。 |
| [getBounds()](#getBounds--) | 画像の境界を取得します。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 内部バッファ全体に対して定義された最大許容サイズであるバッファサイズのヒントを取得します。 |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Image コンテナを取得します。 |
| [getDataStreamContainer()](#getDataStreamContainer--) | オブジェクトのデータストリームを取得します。 |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | 深く調整されたパレットを取得します。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | デフォルトオプションを取得します。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getFileFormat()](#getFileFormat--) | ファイル形式の値を取得します。 |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | ファイル形式を取得します。 |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | ファイル形式を取得します。 |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | ファイル形式を取得します。 |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | 現在の画像に合わせた矩形を取得します。 |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | 現在の画像に合わせた矩形を取得します。 |
| [getHeight()](#getHeight--) | 画像の高さを取得します。 |
| [getInterruptMonitor()](#getInterruptMonitor--) | 割り込みモニターを取得します。 |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | メモリマネージャーを取得します。 |
| [getOriginalOptions()](#getOriginalOptions--) | 元のファイル設定に基づくオプションを取得します。 |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | 描画可能な画像を取得します。 |
| [getPalette()](#getPalette--) | カラーパレットを取得します。 |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | プライベートフォントキャッシュを作成します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 進行状況イベントハンドラ情報を取得します。 |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | 進行状況イベントハンドラ情報を取得します。 |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | 比例高さを取得します。 |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | 比例幅を取得します。 |
| [getSize()](#getSize--) | 画像サイズを取得します。 |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | ソース画像が存在する場合、そのファイルパスを取得します。 |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | オブジェクトがメモリ最適化戦略を使用するかどうかを示す値を取得します |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | ベンチャーライセンスを取得します。 |
| [getWidth()](#getWidth--) | 画像の幅を取得します。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 画像に背景色があるかどうかを示す値を取得します。 |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | 画像のこのインスタンスがロード後に変更されたかどうかを示す値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | 進捗の最大値を取得または設定します |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 進捗を示します。 |
| [isCached()](#isCached--) | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値を取得します。 |
| [isUsePalette()](#isUsePalette--) | 画像パレットが使用されているかどうかを示す値を取得します。 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 指定されたストリームから新しい画像をロードします。 |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | 指定されたストリームから新しい画像をロードします。 |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | 指定されたストリームから新しい画像をロードします。 |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | 指定されたストリームから新しい画像をロードします。 |
| [load(String filePath)](#load-java.lang.String-) | 指定されたファイルから新しい画像をロードします。 |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | 指定されたファイルから新しい画像をロードします。 |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | 指定されたストリームから新しい画像をロードします。 |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | 指定されたストリームから新しい画像をロードします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | この[Image](../../com.aspose.psd/image)のコンテナが設定されたときに呼び出します。 |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | 画像のサイズを変更します。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | 画像のサイズを変更します。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 画像のサイズを変更します。 |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | 高さを比例的にリサイズします。 |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | 高さを比例的にリサイズします。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 高さを比例的にリサイズします。 |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | 幅を比例的にリサイズします。 |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | 幅を比例的にリサイズします。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 幅を比例的にリサイズします。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 画像を回転、フリップ、または回転とフリップを行います。 |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | 自動パレット調整を行うかどうかを示す値を設定します。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 背景色の値を取得または設定します。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | すべての内部バッファに対して許容される最大サイズとして定義されたバッファサイズヒントを設定します。 |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Image コンテナを設定します。 |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | オブジェクトのデータストリームを設定します。 |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 保存後に [ignore after save] かどうかを示す値を設定します。 |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | 画像のこのインスタンスがロード後に変更されたかどうかを示す値を取得または設定します。 |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | 割り込みモニターを設定します。 |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | メモリマネージャーを設定します。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | カラーパレットを設定します。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | 画像パレットを設定します。 |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | すべての Aspose 製品はこのメソッドを実装すべきです。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### cacheData() {#cacheData--}
```
public abstract void cacheData()
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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


aps に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 画像オプション。 |
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
### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


画像の高さを取得します。

**Returns:**
int - 画像の高さ。
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


割り込みモニターを取得します。

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


メモリマネージャーを取得します。

値: メモリマネージャー。

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - メモリマネージャー。
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
### getSize() {#getSize--}
```
public Size getSize()
```


画像サイズを取得します。

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


ソース画像が存在する場合、そのファイルパスを取得します。ソースパスが見つからない場合は空文字列を返します。

**Returns:**
java.lang.String - ソース画像のファイルパスです。
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


オブジェクトがメモリ最適化戦略を使用するかどうかを示す値を取得します

Value:  true  オブジェクトがメモリ最適化戦略を使用する場合; それ以外の場合は  false 。

**Returns:**
boolean - オブジェクトがメモリ最適化戦略を使用するかどうかを示す値です
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


ベンチャーライセンスを取得します。

**Returns:**
java.lang.Object - ベンチャー ライセンスをオブジェクトとして表します。
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


画像の幅を取得します。

**Returns:**
int - 画像の幅。
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
public abstract boolean isCached()
```


オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値を取得します。

**Returns:**
boolean - オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値。
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
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public abstract void resize(int newWidth, int newHeight, int resizeType)
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


画像を回転、フリップ、または回転とフリップを行います。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 回転フリップタイプ | int | 回転フリップのタイプ。 |

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




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


オブジェクトのデータストリームを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | オブジェクトのデータストリーム。 |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


割り込みモニターを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | 割り込みモニター。 |

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
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


画像パレットを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 設定するパレット。 |
| updateColors | boolean | true に設定された場合、色は新しいパレットに従って更新されます。そうでない場合、カラーインデックスは変更されません。インデックスが変更されないと、対応するパレットエントリがないインデックスがある場合、画像の読み込み時にクラッシュする可能性があることに注意してください。 |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


すべての Aspose 製品はこのメソッドを実装すべきです。このメソッドは GroupDocs 製品から呼び出され、GroupDocs 自体がライセンスされているかどうかを示し、カスタム透かしを指定します。GroupDocs がライセンスされている場合、このドキュメント インスタンスも Aspose 製品がライセンスされていなくてもライセンス済みとして動作すべきです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

