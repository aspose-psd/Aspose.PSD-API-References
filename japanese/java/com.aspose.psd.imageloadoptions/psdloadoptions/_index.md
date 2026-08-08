---
title: "PsdLoadOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD のロードオプション"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

PSD のロードオプション
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | 新しい [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) クラスのインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | カスタムフォント ソース |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | レイヤーが変更されていない場合、レンダリング中に元のレイヤーピクセルを保持するかどうかを取得または設定します。 |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | ワープ変換の有無にかかわらず、レンダリングされた画像とともに保存するかどうかを取得または設定します。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 内部バッファ全体に対して定義された最大許容サイズであるバッファサイズのヒントを取得します。 |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | 画像の背景色を取得します。 |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | データ復旧モードを取得します。 |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | ロード後に[ignore after load]かどうかを示す値を取得します。 |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) |  [ignore alpha channel] を無視するかどうかを示す値を取得または設定します。 |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | UpdateText 操作の実行時に PSD テキストレイヤーの固定幅を無視するかどうかを示す値を取得または設定します。 |
| [getLoadEffectsResource()](#getLoadEffectsResource--) |  [load effects resource] をロードするかどうかを示す値を取得または設定します（デフォルトではリソースはロードされません）。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | プログレスイベントハンドラを取得します。 |
| [getReadOnlyMode()](#getReadOnlyMode--) |  [use read only mode] を使用するかどうかを示す値を取得または設定します。 |
| [getReadOnlyType()](#getReadOnlyType--) | PSD 画像をロードする際に使用される読み取り専用モードを取得または設定します。 |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) |  [use disk for load effects resource] を使用するかどうかを示す値を取得または設定します（デフォルトではエフェクトリソースのロードにディスクが使用されますが、この値を false に設定するとメモリが使用可能です）。 |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | ICC プロファイル変換を適用すべきかどうかを示す値を取得します。 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | これはベンチャーライセンスパターンの一部です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | レイヤーが変更されていない場合、レンダリング中に元のレイヤーピクセルを保持するかどうかを取得または設定します。 |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | ワープ変換の有無にかかわらず、レンダリングされた画像とともに保存するかどうかを取得または設定します。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | すべての内部バッファに対して許容される最大サイズとして定義されたバッファサイズヒントを設定します。 |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | 画像の背景色を設定します。 |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | データ復旧モードを設定します。 |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | [ignore after load]かどうかを示す値を設定します。 |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) |  [ignore alpha channel] を無視するかどうかを示す値を取得または設定します。 |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | UpdateText 操作の実行時に PSD テキストレイヤーの固定幅を無視するかどうかを示す値を取得または設定します。 |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) |  [load effects resource] をロードするかどうかを示す値を取得または設定します（デフォルトではリソースはロードされません）。 |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | メモリ MGR を取得または設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | プログレスイベントハンドラを設定します。 |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) |  [use read only mode] を使用するかどうかを示す値を取得または設定します。 |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | PSD 画像をロードする際に使用される読み取り専用モードを取得または設定します。 |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) |  [use disk for load effects resource] を使用するかどうかを示す値を取得または設定します（デフォルトではエフェクトリソースのロードにディスクが使用されますが、この値を false に設定するとメモリが使用可能です）。 |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | ICC プロファイル変換を適用すべきかどうかを示す値を設定します。 |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | これはベンチャーライセンスパターンの一部です。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


新しい [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) クラスのインスタンスを初期化します。

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


レイヤーが変更されていない場合、レンダリング中に元のレイヤーピクセルを保持するかどうかを取得または設定します。

値:  true  は変更されていないレイヤーの元のピクセルを保持します; それ以外は false 。

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


ワープ変換の有無にかかわらず、レンダリングされた画像とともに保存するかどうかを取得または設定します。

値:  true  はワープ変換で画像をレンダリングし、 false 。

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
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


ロード後に[ignore after load]かどうかを示す値を取得します。

**Returns:**
boolean - [ignore after load]の場合は true、そうでない場合は false。
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


 [ignore alpha channel] を無視するかどうかを示す値を取得または設定します。

値:  true  は [ignore alpha channel] の場合; それ以外は false 。

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


UpdateText 操作の実行時に PSD テキストレイヤーの固定幅を無視するかどうかを示す値を取得または設定します。

値:  true  は [ignore text layer width] の場合; それ以外は false 。

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


 [load effects resource] をロードするかどうかを示す値を取得または設定します（デフォルトではリソースはロードされません）。このオプションを設定すると、サポートされているエフェクトのみが最終的な合成画像にレンダリングされます。

値:  true  は [load effects resource] の場合; それ以外は false 。

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


プログレスイベントハンドラを取得します。

値: プログレスイベントハンドラ。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


 [use read only mode] を使用するかどうかを示す値を取得または設定します。これは読み取り専用モードで、Adobe Photoshop と同一の互換性をサポートします。このオプションを設定すると、レイヤーに適用されたすべての変更は最終画像に保存されません。すべてのデータは ImageData セクションから使用されるため、Photoshop と同一です。デフォルトでは、ロードされたすべての画像は Adobe Photoshop 互換ではありません。

値:  true  は [use photoshop compatibility mode] の場合; それ以外は false 。

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


PSD 画像をロードする際に使用される読み取り専用モードを取得または設定します。

値: ReadOnlyMode のいずれかの値 ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-))

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


 [use disk for load effects resource] を使用するかどうかを示す値を取得または設定します（デフォルトではエフェクトリソースのロードにディスクが使用されますが、この値を false に設定するとメモリが使用可能です）。

値: true の場合は [use disk for load effects resource]、それ以外の場合は false。

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


レイヤーが変更されていない場合、レンダリング中に元のレイヤーピクセルを保持するかどうかを取得または設定します。

値:  true  は変更されていないレイヤーの元のピクセルを保持します; それ以外は false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


ワープ変換の有無にかかわらず、レンダリングされた画像とともに保存するかどうかを取得または設定します。

値:  true  はワープ変換で画像をレンダリングし、 false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


[ignore after load]かどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | true  は [ignore after load] の場合; それ以外は false 。 |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


 [ignore alpha channel] を無視するかどうかを示す値を取得または設定します。

値:  true  は [ignore alpha channel] の場合; それ以外は false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


UpdateText 操作の実行時に PSD テキストレイヤーの固定幅を無視するかどうかを示す値を取得または設定します。

値:  true  は [ignore text layer width] の場合; それ以外は false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


 [load effects resource] をロードするかどうかを示す値を取得または設定します（デフォルトではリソースはロードされません）。このオプションを設定すると、サポートされているエフェクトのみが最終的な合成画像にレンダリングされます。

値:  true  は [load effects resource] の場合; それ以外は false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


 [use read only mode] を使用するかどうかを示す値を取得または設定します。これは読み取り専用モードで、Adobe Photoshop と同一の互換性をサポートします。このオプションを設定すると、レイヤーに適用されたすべての変更は最終画像に保存されません。すべてのデータは ImageData セクションから使用されるため、Photoshop と同一です。デフォルトでは、ロードされたすべての画像は Adobe Photoshop 互換ではありません。

値:  true  は [use photoshop compatibility mode] の場合; それ以外は false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


PSD 画像をロードする際に使用される読み取り専用モードを取得または設定します。

値: ReadOnlyMode のいずれかの値 ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-))

 *  
 *  
 *  

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


 [use disk for load effects resource] を使用するかどうかを示す値を取得または設定します（デフォルトではエフェクトリソースのロードにディスクが使用されますが、この値を false に設定するとメモリが使用可能です）。

値: true の場合は [use disk for load effects resource]、それ以外の場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

