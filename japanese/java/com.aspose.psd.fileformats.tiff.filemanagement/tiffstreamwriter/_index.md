---
title: "TiffStreamWriter"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "TIFF ストリームライター。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

TIFF ストリームライター。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | TiffStreamWriter クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | ストリーム位置を取得または設定します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期リソースへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | ストリーム位置を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | 指定されたデータを書き込みます。 |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | 指定されたデータを書き込みます。 |
| [writeDouble(double data)](#writeDouble-double-) | ストリームに単一の double 値を書き込みます。 |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | ストリームに double 値の配列を書き込みます。 |
| [writeFloat(float data)](#writeFloat-float-) | ストリームに単一の float 値を書き込みます。 |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | ストリームに float 値の配列を書き込みます。 |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | ストリームに単一の有理数値を書き込みます。 |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | ストリームに符号なし有理数値の配列を書き込みます。 |
| [writeSByte(byte data)](#writeSByte-byte-) | ストリームに単一の符号付きバイト値を書き込みます。 |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | ストリームに符号付きバイト値の配列を書き込みます。 |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | ストリームに整数値の配列を書き込みます。 |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | ストリームに単一の符号付き有理数値を書き込みます。 |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | ストリームに符号付き有理数値の配列を書き込みます。 |
| [writeSShort(short data)](#writeSShort-short-) | ストリームに単一の short 値を書き込みます。 |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | ストリームに short 値の配列を書き込みます。 |
| [writeSlong(int data)](#writeSlong-int-) | ストリームに単一の整数値を書き込みます。 |
| [writeUByte(byte data)](#writeUByte-byte-) | ストリームに単一のバイト値を書き込みます。 |
| [writeULong(long data)](#writeULong-long-) | ストリームに単一の符号なし整数値を書き込みます。 |
| [writeULongArray(long[] data)](#writeULongArray-long---) | ストリームに符号なし整数値の配列を書き込みます。 |
| [writeUShort(int data)](#writeUShort-int-) | ストリームに単一の符号なし short 値を書き込みます。 |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | ストリームに符号なし short 値の配列を書き込みます。 |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


TiffStreamWriter クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームライターです。 |

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
### getPosition() {#getPosition--}
```
public long getPosition()
```


ストリーム位置を取得または設定します。

値: ストリーム位置です。

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


同期リソースへのアクセスを同期させるために使用できるオブジェクトを取得します。

値: 同期されたリソースへのアクセスを同期するために使用できるオブジェクトです。

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




### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


ストリーム位置を取得または設定します。

値: ストリーム位置です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

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

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


指定されたデータを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | 書き込むデータ。 |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


指定されたデータを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | 書き込むデータ。 |
| オフセット | int | データのオフセット。 |
| データ長 | int | 書き込み対象データの長さ。 |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


ストリームに単一の double 値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | double | 書き込む値。 |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


ストリームに double 値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | double[] | 書き込む配列。 |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


ストリームに単一の float 値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | float | 書き込む値。 |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


ストリームに float 値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | float[] | 書き込む配列。 |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


ストリームに単一の有理数値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | 書き込む値。 |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


ストリームに符号なし有理数値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | 書き込む配列。 |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


ストリームに単一の符号付きバイト値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte | 書き込む値。 |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


ストリームに符号付きバイト値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | 書き込む配列。 |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


ストリームに整数値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | int[] | 書き込む配列。 |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


ストリームに単一の符号付き有理数値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | 書き込む値。 |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


ストリームに符号付き有理数値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | 書き込む配列。 |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


ストリームに単一の short 値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | short | 書き込む値。 |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


ストリームに short 値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | short[] | 書き込む配列。 |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


ストリームに単一の整数値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | int | 書き込む値。 |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


ストリームに単一のバイト値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte | 書き込む値。 |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


ストリームに単一の符号なし整数値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | long | 書き込む値。 |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


ストリームに符号なし整数値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | long[] | 書き込む配列。 |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


ストリームに単一の符号なし short 値を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | int | 書き込む値。 |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


ストリームに符号なし short 値の配列を書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | int[] | 書き込む配列。 |

