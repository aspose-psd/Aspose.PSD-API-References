---
title: "IntRange"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "要素のシーケンスを表すクラス"
type: docs
weight: 62
url: /ja/java/com.aspose.psd/intrange/
---

**Inheritance:**
java.lang.Object
```
public class IntRange
```

要素のシーケンスを表すクラス
## Constructors

| Constructor | 説明 |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | IntRange クラスの新しいインスタンスを初期化します。 |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | IntRange クラスの新しいインスタンスを初期化します。 |
| [IntRange(int[] range)](#IntRange-int---) | IntRange クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | 指定されたインデックスから 1 要素の配列を返します。 |
| [getClass()](#getClass--) |  |
| [getRange()](#getRange--) | 範囲を取得します。 |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | start から開始する int 要素のカウント範囲を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRange(int[] value)](#setRange-int---) | 範囲を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


IntRange クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 開始 | int | 開始。 |
| count | int | カウントです。 |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


IntRange クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 開始 | int | 開始。 |
| count | int | カウントです。 |
| デルタ | int | デルタ。 |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


IntRange クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 範囲 | int[] | 範囲。 |

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
### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


指定されたインデックスから 1 要素の配列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 範囲インデックス。 |

**Returns:**
int[] - System.Int32 の配列
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getRange() {#getRange--}
```
public int[] getRange()
```


範囲を取得します。

**Returns:**
int[] - 範囲。
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


start から開始する int 要素のカウント範囲を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 開始 | int | 開始。 |
| count | int | カウントです。 |
| デルタ | int | デルタ。 |

**Returns:**
int[] - アイテムの配列
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




### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


範囲を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | 範囲。 |

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

