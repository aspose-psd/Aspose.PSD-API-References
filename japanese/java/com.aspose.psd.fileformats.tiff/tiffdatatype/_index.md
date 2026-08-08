---
title: "TiffDataType"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "TIFF データ型。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

TIFF データ型。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | 現在のインスタンスを同じ型の別のオブジェクトと比較し、現在のインスタンスがソート順で前に来るか、後に来るか、または同じ位置にあるかを示す整数を返します。 |
| [deepClone()](#deepClone--) | このインスタンスのディープクローンを実行します。 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | タグデータを収めるのに 12 バイトでは不足する場合に備えて、追加データサイズ（バイト単位）を取得します。 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 要素数を取得します。 |
| [getDataSize()](#getDataSize--) | タグデータを収めるのに 12 バイトでは不足する場合に備えて、追加データサイズ（バイト単位）を取得します。 |
| [getId()](#getId--) | タグ ID の整数表現を取得します。 |
| [getTagId()](#getTagId--) | タグ ID を取得します。 |
| [getTagType()](#getTagType--) | タグのタイプを取得します。 |
| [getValue()](#getValue--) | このデータ型が含む値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | タグがプライベートかどうかを示す値を取得します。 |
| [isValid()](#isValid--) | タグデータが有効かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | タグデータを読み取ります。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | このデータ型が含む値を設定します。 |
| [toString()](#toString--) | このインスタンスを表す  System.String  を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | 追加のタグデータを書き込みます。 |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | タグデータを書き込みます。 |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


現在のインスタンスを同じ型の別のオブジェクトと比較し、現在のインスタンスがソート順で前に来るか、後に来るか、または同じ位置にあるかを示す整数を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | このインスタンスと比較するオブジェクト。 |

**Returns:**
int - 比較されるオブジェクトの相対順序を示す 32 ビット符号付き整数です。戻り値は次の意味を持ちます: 値の意味 負の数 このインスタンスは obj 未満です。 ゼロ このインスタンスは obj と等しいです。 正の数 このインスタンスは obj より大きいです。
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


このインスタンスのディープクローンを実行します。

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


タグデータを収めるのに 12 バイトでは不足する場合に備えて、追加データサイズ（バイト単位）を取得します。

**Returns:**
long - 追加データのサイズ（バイト単位）。

これはデータバイト数をワード境界に合わせたものです。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


要素数を取得します。

**Returns:**
long - 要素数。
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


タグデータを収めるのに 12 バイトでは不足する場合に備えて、追加データサイズ（バイト単位）を取得します。

**Returns:**
long - 追加データのサイズ（バイト単位）。

これは正確なバイト数です。
### getId() {#getId--}
```
public int getId()
```


タグ ID の整数表現を取得します。

**Returns:**
int - タグ ID の整数表現
### getTagId() {#getTagId--}
```
public int getTagId()
```


タグ ID を取得します。

**Returns:**
int - タグ ID。
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


タグのタイプを取得します。

**Returns:**
int - タグのタイプ。
### getValue() {#getValue--}
```
public abstract Object getValue()
```


このデータ型が含む値を取得します。

**Returns:**
java.lang.Object - 値。
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


タグがプライベートかどうかを示す値を取得します。プライベート TIFF タグはタグ ID が 32768 を超えるタグです。

**Returns:**
boolean - タグデータが有効な場合は true、そうでない場合は false。
### isValid() {#isValid--}
```
public boolean isValid()
```


タグデータが有効かどうかを示す値を取得します。有効なタグは保存できるデータを含みます。無効なタグは保存できません。

**Returns:**
boolean - タグデータが有効な場合は true、そうでない場合は false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


タグデータを読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | データストリーム。 |
| position | long | タグの位置。 |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


このデータ型が含む値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object | 値です。 |

### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す  System.String  を返します。

**Returns:**
java.lang.String - このインスタンスを表す System.String。
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


追加のタグデータを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | データストリーム。 |

**Returns:**
long - 実際に書き込まれたバイト数。
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


タグデータを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | データストリーム。 |
| additionalDataOffset | long | 追加データを書き込むオフセット。 |

