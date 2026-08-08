---
title: "MultiPageOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "複数ページをサポートする形式の基底クラスです"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

複数ページをサポートする形式の基底クラスです
## Constructors

| Constructor | 説明 |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | MultiPageOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | エクスポート領域を取得または設定します。 |
| [getMergeLayers()](#getMergeLayers--) | [merege layers] を示す値を取得します。 |
| [getMode()](#getMode--) | モードを取得または設定します。 |
| [getOutputLayersNames()](#getOutputLayersNames--) | 出力レイヤー名を取得または設定します（エクスポート形式がレイヤー名付けをサポートしている場合に機能します。例: Psd）。 |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | ページのラスタライズオプションを取得します。 |
| [getPageTitles()](#getPageTitles--) | ページタイトルを取得または設定します。 |
| [getPages()](#getPages--) | ページを取得または設定します。 |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | 時間間隔を取得します。 |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | 範囲配列からページを初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | エクスポート領域を取得または設定します。 |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | [merege layers] を示す値を設定します。 |
| [setMode(int value)](#setMode-int-) | モードを取得または設定します。 |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | 出力レイヤー名を取得または設定します（エクスポート形式がレイヤー名付けをサポートしている場合に機能します。例: Psd）。 |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | ページのラスタライズオプションを設定します。 |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | ページタイトルを取得または設定します。 |
| [setPages(int[] value)](#setPages-int---) | ページを取得または設定します。 |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | 時間間隔を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ページ | int[] | ページです。 |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ページ | int[] | ページの配列です。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | エクスポート領域です。 |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | ページタイトルです。 |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | ページタイトルです。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | エクスポート領域です。 |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | IntRangeです。 |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | IntRangeです。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | エクスポート領域です。 |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | IntRangeです。 |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | IntRangeです。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | エクスポート領域です。 |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ページ | int | ページインデックスです。 |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


MultiPageOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ページ | int | ページインデックスです。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | エクスポート領域です。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


エクスポート領域を取得または設定します。

値: エクスポート領域です。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


[merege layers] を示す値を取得します。

値: true が [merege layers] の場合; それ以外は false。

**Returns:**
boolean - [merege layers] を示す値です。
### getMode() {#getMode--}
```
public int getMode()
```


モードを取得または設定します。

値: モードです。

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


出力レイヤー名を取得または設定します（エクスポート形式がレイヤー名付けをサポートしている場合に機能します。例: Psd）。

値: 出力レイヤー名です。

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


ページのラスタライズオプションを取得します。

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - ページラスタライズオプションです。
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


ページタイトルを取得または設定します。

値: ページタイトルです。

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


ページを取得または設定します。

値: ページです。

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


時間間隔を取得します。

値: 時間間隔です。

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


範囲配列からページを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | 範囲です。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


エクスポート領域を取得または設定します。

値: エクスポート領域です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


[merege layers] を示す値を設定します。

値: true が [merege layers] の場合; それ以外は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | [merege layers] を示す値です。 |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


モードを取得または設定します。

値: モードです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


出力レイヤー名を取得または設定します（エクスポート形式がレイヤー名付けをサポートしている場合に機能します。例: Psd）。

値: 出力レイヤー名です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


ページのラスタライズオプションを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | ページラスタライズオプションです。 |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


ページタイトルを取得または設定します。

値: ページタイトルです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


ページを取得または設定します。

値: ページです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


時間間隔を設定します。

値: 時間間隔です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | 時間間隔です。 |

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

