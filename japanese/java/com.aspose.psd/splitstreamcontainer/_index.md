---
title: "SplitStreamContainer"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ストリームを保持し、ストリーム処理ルーチンを提供する分割ストリーム コンテナを表します。"
type: docs
weight: 102
url: /ja/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

ストリームを保持し、ストリーム処理ルーチンを提供する分割ストリーム コンテナを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | 新しい [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) クラスのインスタンスを初期化します。 |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | 新しい [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) クラスのインスタンスを初期化します。 |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | 新しい [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) クラスのインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | シーケンシャルに読み取る際の読み取りおよび書き込みバイト数を指定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [canRead()](#canRead--) | ストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| [canSeek()](#canSeek--) | ストリームがシークをサポートしているかどうかを示す値を取得します。 |
| [canWrite()](#canWrite--) | ストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | このストリームのすべてのバッファをクリアし、バッファされたデータが基になるデバイスに書き込まれるようにします。 |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getLength()](#getLength--) | ストリームの長さ（バイト単位）を取得または設定します。 |
| [getPosition()](#getPosition--) | ストリーム内の現在の位置を取得または設定します。 |
| [getStream()](#getStream--) | データストリームを取得します。 |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | 同期リソースへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | ストリームコンテナを指定された位置に挿入します。 |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | このストリームがクローズ時に破棄されるかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | 指定されたバイトバッファを埋めるためにバイトを読み取ります。 |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | 現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| [readByte()](#readByte--) | ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めます。ストリームの末尾に達した場合は -1 を返します。 |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | ストリームのすべてのデータを指定されたストリームに保存（コピー）します。 |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| [save(String filePath)](#save-java.lang.String-) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | 現在のストリーム内の位置を設定します。 |
| [seekBegin()](#seekBegin--) | ストリームの位置をストリームの先頭に設定します。 |
| [setLength(long value)](#setLength-long-) | ストリームの長さ（バイト単位）を取得または設定します。 |
| [setPosition(long value)](#setPosition-long-) | ストリーム内の現在の位置を取得または設定します。 |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | ストリームデータをバイト配列に変換します。 |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | ストリームデータをバイト配列に変換します。 |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | com.aspose.imaging.StreamContainer から System.IO.Stream への明示的な変換を実行します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | 指定されたすべてのバイトを書き込みます。 |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | バイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。 |
| [writeByte(byte value)](#writeByte-byte-) | ストリームの現在位置に 1 バイトを書き込み、ストリーム内の位置を 1 バイト進めます。 |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | 含まれるデータを別の StreamContainer にコピーします。 |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | 含まれるデータを別の StreamContainer にコピーします。 |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


新しい [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ストリーム。 |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


新しい [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | データストリーム。 |
| disposeStream | boolean | true に設定された場合、コンテナが破棄されるときにストリームも破棄されます。 |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


新しい [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| disposeStream | boolean | true に設定された場合、ストリームを破棄します。 |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


シーケンシャルに読み取る際の読み取りおよび書き込みバイト数を指定します。

### canRead() {#canRead--}
```
public boolean canRead()
```


ストリームが読み取りをサポートしているかどうかを示す値を取得します。

値: 読み取りをサポートするストリームの場合は true、そうでない場合は false。

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


ストリームがシークをサポートしているかどうかを示す値を取得します。

値: シークをサポートするストリームの場合は true、そうでない場合は false。

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


ストリームが書き込みをサポートしているかどうかを示す値を取得します。

値: 書き込みをサポートするストリームの場合は true、そうでない場合は false。

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Closable インターフェイスを実装し、JDK 1.7 以降の try-with-resources 文で使用できます。このメソッドは単に dispose メソッドを呼び出すだけです。

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

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
### flush() {#flush--}
```
public void flush()
```


このストリームのすべてのバッファをクリアし、バッファされたデータが基になるデバイスに書き込まれるようにします。

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
### getLength() {#getLength--}
```
public long getLength()
```


ストリームの長さ（バイト単位）を取得または設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置分だけ System.IO.Stream.Length より小さくなります。

値: ストリームの長さ。

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


ストリーム内の現在位置を取得または設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。

値: 現在のストリーム位置。

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


データストリームを取得します。

値: データストリーム。

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
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
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


ストリームコンテナを指定された位置に挿入します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | int | 挿入先の位置。 |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | 挿入するストリームコンテナ。 |
| disposeStream | boolean | true に設定された場合、ストリームを破棄します。 |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


このストリームがクローズ時に破棄されるかどうかを示す値を取得します。

値: クローズ時にストリームが破棄される場合は true、そうでない場合は false。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


指定されたバイトバッファを埋めるためにバイトを読み取ります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バイト | byte[] | 埋めるバイト。 |

**Returns:**
int - 読み取られたバイト数。この値は、ストリームに十分なバイトがない場合、バッファ内のバイト数より少なくなることがあります。
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バッファ | byte[] | バイト配列。このメソッドが戻ると、バッファには指定されたバイト配列が含まれ、offset から (offset + count - 1) までの値が現在のソースから読み取られたバイトで置き換えられます。 |
| オフセット | int | 現在のストリームから読み取ったデータの格納を開始する、バッファ内のゼロベースのバイトオフセット。 |
| count | int | 現在のストリームから読み取る最大バイト数。 |

**Returns:**
int - バッファに読み取られたバイトの総数。要求されたバイト数が現在利用できない場合はそれ未満になることがあり、ストリームの終端に達した場合は 0 になります。
### readByte() {#readByte--}
```
public int readByte()
```


ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めます。ストリームの末尾に達した場合は -1 を返します。

**Returns:**
int - unsigned バイトを Int32 にキャストした値、またはストリームの終端の場合は -1。
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ ReadWriteBytesCount とストリーム Length の値を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | データを保存するストリーム。 |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


指定されたストリームにストリームのデータをすべて保存（コピー）します。ストリームの Length 値を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | データを保存するストリーム。 |
| bufferSize | int | バッファ。 |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


ストリームのデータを指定されたストリームに保存（コピー）します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dstStream | java.io.OutputStream | データを保存するストリーム。 |
| bufferSize | int | バッファサイズです。デフォルトでは [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT) の値が使用されます。 |
| length | long | コピーするストリームデータの長さです。デフォルトでは長さが Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)) の値に設定されます。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ ReadWriteBytesCount とストリーム Length の値を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ストリームデータを保存するファイルパスです。 |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


指定されたストリームにストリームのデータを保存（コピー）します。ストリームの Length 値を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ストリームデータを保存するファイルパスです。 |
| bufferSize | int | バッファサイズです。デフォルトでは ReadWriteBytesCount の値が使用されます。 |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


ストリームのデータを指定されたストリームに保存（コピー）します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ストリームデータを保存するファイルパスです。 |
| bufferSize | int | バッファサイズです。デフォルトでは ReadWriteBytesCount の値が使用されます。 |
| length | long | コピーするストリームデータの長さです。デフォルトでは長さが Length の値に設定されます。 |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| length | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


現在のストリーム内の位置を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| オフセット | long | origin パラメータに対するバイトオフセットです。この値は StreamContainer コンストラクタで渡された開始ストリーム位置からのオフセットを表します。 |
| origin | int | 新しい位置を取得する際に使用される基準点を示す [SeekOrigin](../../com.aspose.psd/seekorigin) 型の値です。 |

**Returns:**
long - 現在のストリーム内の新しい位置です。
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


ストリーム位置をストリームの先頭に設定します。この値は StreamContainer コンストラクタで渡された開始ストリーム位置からのオフセットを表します。

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


ストリームの長さ（バイト単位）を取得または設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置分だけ System.IO.Stream.Length より小さくなります。

値: ストリームの長さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


ストリーム内の現在位置を取得または設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。

値: 現在のストリーム位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


ストリームデータをバイト配列に変換します。

**Returns:**
byte[] - ストリームデータをバイト配列に変換したものです。
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


ストリームデータをバイト配列に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | long | バイトの読み取りを開始する位置です。 |
| bytesCount | long | 読み取るバイト数です。 |

**Returns:**
byte[] - ストリームデータをバイト配列に変換したものです。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


com.aspose.imaging.StreamContainer から System.IO.Stream への明示的な変換を実行します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |

**Returns:**
com.aspose.ms.System.IO.Stream - 変換の結果です。
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


指定されたすべてのバイトを書き込みます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バイト | byte[] | 書き込むバイトです。 |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


バイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バッファ | byte[] | バイト配列です。このメソッドは buffer から count バイトを現在のストリームにコピーします。 |
| オフセット | int | 現在のストリームにバイトのコピーを開始する buffer 内のゼロベースのバイトオフセットです。 |
| count | int | 現在のストリームに書き込むバイト数です。 |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


ストリームの現在位置に 1 バイトを書き込み、ストリーム内の位置を 1 バイト進めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte | ストリームに書き込むバイトです。 |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


含まれるデータを別の StreamContainer にコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | コピー先のストリームコンテナです。 |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


含まれるデータを別の StreamContainer にコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | コピー先のストリームコンテナです。 |
| length | long | 書き込むバイト数です。 |

