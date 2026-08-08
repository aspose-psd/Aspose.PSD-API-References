---
title: "TiffStreamReader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "リトルエンディアン TIFF ファイル形式を処理するための TIFF ストリームです。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

リトルエンディアン TIFF ファイル形式を処理するための TIFF ストリームです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | TiffStreamReader クラスの新しいインスタンスを初期化します。 |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | TiffStreamReader クラスの新しいインスタンスを初期化します。 |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | TiffStreamReader クラスの新しいインスタンスを初期化します。 |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | TiffStreamReader クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | リーダーの長さを取得します。 |
| [getThrowExceptions()](#getThrowExceptions--) | 不正なデータ処理（ストリームの読み取りまたは書き込み）時に例外がスローされるかどうかを示す値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | ストリームからバイト値の配列を読み取ります。 |
| [readBytes(long position, long count)](#readBytes-long-long-) | ストリームから符号なしバイト値の配列を読み取ります。 |
| [readDouble(long position)](#readDouble-long-) | ストリームから単一の double 値を読み取ります。 |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | ストリームから double 値の配列を読み取ります。 |
| [readFloat(long position)](#readFloat-long-) | ストリームから単一の float 値を読み取ります。 |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | ストリームから float 値の配列を読み取ります。 |
| [readRational(long position)](#readRational-long-) | ストリームから単一の有理数値を読み取ります。 |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | ストリームから有理数の配列を読み取ります。 |
| [readSByte(long position)](#readSByte-long-) | ストリームから符号付きバイトデータを読み取ります。 |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | ストリームから符号付きバイト値の配列を読み取ります。 |
| [readSLong(long position)](#readSLong-long-) | ストリームから符号付き整数値を読み取ります。 |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | ストリームから符号付き整数値の配列を読み取ります。 |
| [readSRational(long position)](#readSRational-long-) | ストリームから単一の符号付き有理数値を読み取ります。 |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | ストリームから符号付き有理数の配列を読み取ります。 |
| [readSShort(long position)](#readSShort-long-) | ストリームから符号付きショート値を読み取ります。 |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | ストリームから符号付きショート値の配列を読み取ります。 |
| [readString_internalized(long position)](#readString-internalized-long-) | ストリームから文字列を読み取ります。 |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | ストリームから文字列を読み取ります。 |
| [readULong(long position)](#readULong-long-) | ストリームから符号なし整数値を読み取ります。 |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | ストリームから符号なし整数値の配列を読み取ります。 |
| [readUShort(long position)](#readUShort-long-) | ストリームから符号なしショート値を読み取ります。 |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | ストリームから符号なし整数値の配列を読み取ります。 |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | 不正なデータ処理（ストリームの読み取りまたは書き込み）時に例外がスローされるかどうかを示す値を取得または設定します。 |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | 基礎データをストリームコンテナに変換します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


TiffStreamReader クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | バイト配列データです。 |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


TiffStreamReader クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | バイト配列データです。 |
| startIndex | int | データへの開始インデックスです。 |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


TiffStreamReader クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | バイト配列データです。 |
| startIndex | int | データへの開始インデックスです。 |
| データ長 | int | データの長さです。 |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


TiffStreamReader クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |

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
### getLength() {#getLength--}
```
public long getLength()
```


リーダーの長さを取得します。

値: リーダーの長さです。

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


不正なデータ処理（ストリームの読み取りまたは書き込み）時に例外がスローされるかどうかを示す値を取得または設定します。

Value: データ処理が正しくない場合に例外がスローされる場合は true、そうでない場合はエラー条件が黙って無視されます。

**Returns:**
boolean
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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


ストリームからバイト値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 配列 | byte[] | 埋める配列です。 |
| arrayIndex | int | 値を設定し始める配列インデックス。 |
| position | long | 読み込むストリームの位置。 |
| count | long | 読み取る要素の数。 |

**Returns:**
long - バイト値の配列。
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


ストリームから符号なしバイト値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
byte[] - 符号なしバイト値の配列。
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


ストリームから単一の double 値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
double - 単一の double 値。
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


ストリームから double 値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
double[] - double 値の配列。
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


ストリームから単一の float 値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
float - 単一の float 値。
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


ストリームから float 値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
float[] - float 値の配列。
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


ストリームから単一の有理数値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


ストリームから有理数の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - 有理数の配列。
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


ストリームから符号付きバイトデータを読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
byte - 符号付きバイト値。
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


ストリームから符号付きバイト値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
byte[] - 符号付きバイト値の配列。
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


ストリームから符号付き整数値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
int - 符号付き整数値。
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


ストリームから符号付き整数値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
int[] - 符号付き整数値の配列。
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


ストリームから単一の符号付き有理数値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


ストリームから符号付き有理数の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - 符号付き有理数の配列。
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


ストリームから符号付きショート値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
short - 符号付き short 値。
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


ストリームから符号付きショート値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
short[] - 符号付き short 値の配列。
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


ストリームから文字列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 位置。 |

**Returns:**
java.lang.String - 文字列。
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


ストリームから文字列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 位置。 |
| length | long | 長さ。 |

**Returns:**
java.lang.String - 文字列。
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


ストリームから符号なし整数値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
long - 符号なし整数値。
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


ストリームから符号なし整数値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
long[] - 符号なし整数値の配列。
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


ストリームから符号なしショート値を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |

**Returns:**
int - 符号なしショート値。
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


ストリームから符号なし整数値の配列を読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | 読み取り位置。 |
| count | long | 要素数。 |

**Returns:**
int[] - 符号なし整数値の配列。
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


不正なデータ処理（ストリームの読み取りまたは書き込み）時に例外がスローされるかどうかを示す値を取得または設定します。

Value: データ処理が正しくない場合に例外がスローされる場合は true、そうでない場合はエラー条件が黙って無視されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


基礎データをストリームコンテナに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startPosition | long | 変換を開始する開始位置。 |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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

