---
title: "Jpeg2000LoadOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "JPEG2000 のロードオプション"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

JPEG2000 のロードオプション
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | 新しいインスタンスを初期化します  Jpeg2000LoadOptions  クラス。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | カスタムフォント ソース |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | 内部バッファ全体に対して定義された最大許容サイズであるバッファサイズのヒントを取得します。 |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | 画像の背景色を取得します。 |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | データ復旧モードを取得します。 |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | デフォルトの最大デコード時間を取得します。 |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | ロード後に[ignore after load]かどうかを示す値を取得します。 |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | 最大デコード時間（秒）を取得します（このオプションは、メモリが非常に少ない遅いマシンで、解像度が5500x6500ピクセルを超える非常に大きな画像の処理がハングするのを防ぐために使用できます）。 |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | タイルの最大デコード時間を取得します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | プログレスイベントハンドラを取得します。 |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | ICC プロファイル変換を適用すべきかどうかを示す値を取得します。 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | これはベンチャーライセンスパターンの一部です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | すべての内部バッファに対して許容される最大サイズとして定義されたバッファサイズヒントを設定します。 |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | 画像の背景色を設定します。 |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | データ復旧モードを設定します。 |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | デフォルトの最大デコード時間を設定します。 |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | [ignore after load]かどうかを示す値を設定します。 |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | 最大デコード時間（秒）を設定します（このオプションは、メモリが非常に少ない遅いマシンで、解像度が5500x6500ピクセルを超える非常に大きな画像の処理がハングするのを防ぐために使用できます）。 |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | タイルの最大デコード時間を設定します。 |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | メモリ MGR を取得または設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | プログレスイベントハンドラを設定します。 |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | ICC プロファイル変換を適用すべきかどうかを示す値を設定します。 |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | これはベンチャーライセンスパターンの一部です。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


新しいインスタンスを初期化します  Jpeg2000LoadOptions  クラス。

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


カスタムフォント ソース

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
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


画像の背景色を取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

通常、データ破損によりピクセル値が復元できない場合は背景色が設定されます。
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


データ復旧モードを取得します。

**Returns:**
int - データ復旧モード。
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


デフォルトの最大デコード時間を取得します。

**Returns:**
int - デフォルトの最大デコード時間。
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


ロード後に[ignore after load]かどうかを示す値を取得します。

**Returns:**
boolean - [ignore after load]の場合は true、そうでない場合は false。
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


最大デコード時間（秒）を取得します（このオプションは、メモリが非常に少ない遅いマシンで、解像度が5500x6500ピクセルを超える非常に大きな画像の処理がハングするのを防ぐために使用できます）。

**Returns:**
int - 最大デコード時間。
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


タイルの最大デコード時間を取得します。

値: タイルの最大デコード時間。

**Returns:**
int - タイルの最大デコード時間。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


プログレスイベントハンドラを取得します。

値: プログレスイベントハンドラ。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


ICC プロファイル変換を適用すべきかどうかを示す値を取得します。

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


これはベンチャーライセンスパターンの一部です。ベンチャーが LoadOptions オブジェクトを渡すと、VentureLicenser によってこの値が設定されます。

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


画像の背景色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | 背景色。 |

通常、データ破損によりピクセル値が復元できない場合、背景色が設定されます。 |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


データ復旧モードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | データ復旧モードです。 |

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


デフォルトの最大デコード時間を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | デフォルトの最大デコード時間です。 |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


[ignore after load]かどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | true  は [ignore after load] の場合; それ以外は false 。 |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


最大デコード時間（秒）を設定します（このオプションは、メモリが非常に少ない遅いマシンで、解像度が5500x6500ピクセルを超える非常に大きな画像の処理がハングするのを防ぐために使用できます）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 最大デコード時間です。 |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


タイルの最大デコード時間を設定します。

値: タイルの最大デコード時間。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | タイルの最大デコード時間です。 |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


メモリ MGR を取得または設定します。

値: メモリ MGR。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


プログレスイベントハンドラを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | プログレスイベントハンドラです。 |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


ICC プロファイル変換を適用すべきかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


これはベンチャーライセンスパターンの一部です。ベンチャーが LoadOptions オブジェクトを渡すと、VentureLicenser によってこの値が設定されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

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

