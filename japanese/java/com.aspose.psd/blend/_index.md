---
title: "Blend"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ブレンドパターンを定義します。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

ブレンド パターンを定義します。このクラスは継承できません。

典型的な Blend クラスの使用方法は、ブラシ用のブレンド パターンを定義することです。そのため、Blend プロパティは慎重に初期化する必要があります。null 配列は許可されません。ブレンド ファクターまたは位置配列が空であるか、長さが一致しない場合、ブラシは適切な例外をスローします。位置配列に 2 つ以上の要素がある場合、最初の要素は 0、最後の要素は 1 でなければなりません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Blend()](#Blend--) | Blend クラスの新しいインスタンスを初期化します。 |
| [Blend(int count)](#Blend-int-) | 指定されたファクター数と位置数で Blend クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが com.aspose.psd.Blend クラスであり、この com.aspose.psd.Blend クラスと等価かどうかをテストします。 |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | グラデーションのブレンド ファクター配列を取得します。 |
| [getPositions()](#getPositions--) | グラデーションのブレンド 位置配列を取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | グラデーションのブレンド ファクター配列を設定します。 |
| [setPositions(float[] value)](#setPositions-float---) | グラデーションのブレンド 位置配列を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Blend クラスの新しいインスタンスを初期化します。ファクター配列とブレンド配列の要素数は 1 になります。

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


指定されたファクター数と位置数で Blend クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| count | int | ファクター配列と位置配列の要素数。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが com.aspose.psd.Blend クラスであり、この com.aspose.psd.Blend クラスと等価かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象のオブジェクトです。 |

**Returns:**
boolean - obj がこの com.aspose.psd.Blend クラスと等価な com.aspose.psd.Blend クラスである場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


グラデーションのブレンド ファクター配列を取得します。

**Returns:**
float[] - 対応する位置で使用される開始色と終了色の割合を指定するブレンド ファクター配列。
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


グラデーションのブレンド 位置配列を取得します。

**Returns:**
float[] - グラデーションラインに沿った距離の割合を指定するブレンド 位置配列。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコード。ハッシュアルゴリズムやハッシュテーブルのようなデータ構造での使用に適しています。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


グラデーションのブレンド ファクター配列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float[] | 対応する位置で使用される開始色と終了色の割合を指定するブレンド ファクター配列。 |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


グラデーションのブレンド 位置配列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float[] | グラデーションラインに沿った距離の割合を指定するブレンド 位置配列。 |

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

