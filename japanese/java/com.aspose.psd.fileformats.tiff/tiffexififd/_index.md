---
title: "TiffExifIfd"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "TIFF Exif 画像ファイルディレクトリクラス。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

TIFF Exif 画像ファイルディレクトリクラス。

Exif IFD へのポインタをカプセル化します。Interoperability、Exif IFD は TIFF で指定された IFD と同じ構造を持ちます。ただし、通常は TIFF の場合と同様に画像データを含みません。詳細については http://www.exiv2.org/tags.html と http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html を参照してください。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | TiffExifIfd クラスの新しいインスタンスを初期化します。 |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | TiffExifIfd クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | EXIF IFD へのポインタを取得または設定します。 |
| [hasValue()](#hasValue--) | このインスタンスが値を持つかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | EXIF IFD へのポインタを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


TiffExifIfd クラスの新しいインスタンスを初期化します。

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


TiffExifIfd クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ifdOffset | long | Exif IFD へのポインタです。 |

Interoperability、Exif IFD は TIFF で指定された IFD と同じ構造を持ちます。ただし、通常は TIFF の場合と同様に画像データを含みません。 |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


EXIF IFD へのポインタを取得または設定します。

**Returns:**
long - EXIF IFD へのポインタ。
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


このインスタンスが値を持つかどうかを示す値を取得します。

**Returns:**
boolean - このインスタンスが値を持つ場合は true、そうでない場合は false。
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




### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


EXIF IFD へのポインタを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | EXIF IFD へのポインタです。 |

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

