---
title: "ProgressEventHandlerInfo"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "このクラスは、画像のロード/保存/エクスポート操作の進捗に関する情報を表し、外部アプリケーションで変換の進捗をエンドユーザーに表示するために使用できます。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

このクラスは、画像のロード/保存/エクスポート操作の進捗に関する情報を表し、外部アプリケーションで変換進捗をエンドユーザーに表示するために使用できます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | 進捗イベントハンドラを追加します。 |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | イベントの説明を取得します |
| [getEventType()](#getEventType--) | イベントのタイプを取得します。 |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | 最新の進捗イベントハンドラを取得します。 |
| [getMaxValue()](#getMaxValue--) | 上限の進捗値を取得します。 |
| [getValue()](#getValue--) | 現在の進捗値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 進捗を示します。 |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | 進捗を示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | 上限の進捗値。 |
| [setValue_internalized(int value)](#setValue-internalized-int-) | 現在の進捗値。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


進捗イベントハンドラを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 進捗イベントハンドラ。 |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| total | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


イベントの説明を取得します

値: 説明。

**Returns:**
java.lang.String - イベントの説明
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


イベントのタイプを取得します。

値: イベントの型。

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


最新の進捗イベントハンドラを取得します。

値: 最新の進捗イベントハンドラ。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


上限の進捗値を取得します。

値: 進捗の上限値。

**Returns:**
int - 進捗の上限値。
### getValue() {#getValue--}
```
public final int getValue()
```


現在の進捗値を取得します。

値: 進捗値。

**Returns:**
int - 現在の進捗値。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


進捗を示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | イベントの型。 |

**Returns:**
boolean - 成功した場合は true、そうでない場合は false
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


進捗を示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | イベントの型。 |
| 値 | int | 値です。 |

**Returns:**
boolean - 成功した場合は true、そうでない場合は false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


上限の進捗値。

値: 進捗の上限値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 進捗の上限値。 |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


現在の進捗値。

値: 進捗値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 現在の進捗値。 |

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

