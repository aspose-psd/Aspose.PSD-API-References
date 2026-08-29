---
title: "クラス SplitStreamContainer"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.SplitStreamContainer クラス。ストリームを保持し、ストリーム処理ルーチンを提供する分割ストリームコンテナを表します"
type: docs
weight: 6130
url: /ja/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

ストリームを保持し、ストリーム処理ルーチンを提供する分割ストリームコンテナを表します。

```csharp
public class SplitStreamContainer : StreamContainer
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | `SplitStreamContainer` クラスの新しいインスタンスを初期化します。 |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | `SplitStreamContainer` クラスの新しいインスタンスを初期化します。 |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | `SplitStreamContainer` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | ストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | ストリームがシークをサポートしているかどうかを示す値を取得します。 |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | ストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | このストリームがクローズ時に破棄されるかどうかを示す値を取得します。 |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | ストリームの長さ（バイト単位）を取得または設定します。この値は、StreamContainer コンストラクタで渡された開始ストリーム位置分だけ Length より小さくなります。 |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | ストリーム内の現在位置を取得または設定します。この値は、StreamContainer コンストラクタで渡された開始ストリーム位置からのオフセットを表します。 |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | データストリームを取得します。 |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | 同期されたリソースへのアクセスを同期させるために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | このストリームのすべてのバッファをクリアし、バッファされたデータを基になるデバイスに書き込ませます。 |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | ストリームコンテナを指定された位置に挿入します。 |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | 指定されたバイトバッファを埋めるためにバイトを読み取ります。 |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | 現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | ストリームから1バイトを読み取り、ストリーム内の位置を1バイト進めます。ストリームの末尾に達した場合は -1 を返します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) とストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) とストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | ストリームのすべてのデータを指定されたストリームに保存（コピー）します。ストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | ストリームのデータを指定されたストリームに保存（コピー）します。ストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | 現在のストリーム内の位置を設定します。 |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | ストリームの位置をストリームの先頭に設定します。この値は、StreamContainer コンストラクタに渡された開始ストリーム位置からのオフセットを表します。 |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | ストリームデータを Byte 配列に変換します。 |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | ストリームデータを Byte 配列に変換します。 |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | 指定されたすべてのバイトを書き込みます。 |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | バイトのシーケンスを現在のストリームに書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。 |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | ストリームの現在位置に1バイトを書き込み、ストリーム内の位置を1バイト進めます。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 含まれるデータを別の [`StreamContainer`](../streamcontainer/) にコピーします。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 含まれるデータを別の [`StreamContainer`](../streamcontainer/) にコピーします。 |

### 関連項目

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


