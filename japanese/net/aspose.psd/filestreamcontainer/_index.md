---
title: "クラス FileStreamContainer"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileStreamContainer クラス。ファイルストリーム処理のためのヘルパーです。"
type: docs
weight: 4720
url: /ja/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

ファイルストリーム処理のヘルパー。

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | ストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | ストリームがシークをサポートしているかどうかを示す値を取得します。 |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | ストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | ファイルパスを取得します。 |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | ストリームが明示的に作成されたかどうかを示す値を取得します。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | このストリームがクローズ時に破棄されるかどうかを示す値を取得します。 |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | ストリームが一時的かどうかを示す値を取得または設定します。 |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | ストリームの長さ（バイト単位）を取得または設定します。この値は、StreamContainer コンストラクタで渡された開始ストリーム位置分だけ Length より小さくなります。 |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | ストリーム内の現在位置を取得または設定します。この値は、StreamContainer コンストラクタで渡された開始ストリーム位置からのオフセットを表します。 |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | データストリームを取得します。 |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | 同期されたリソースへのアクセスを同期させるために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | 新しいファイルストリームを作成します。 |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | 既存のファイルストリームを開きます。ファイルストリームが存在しない場合、適切な例外がスローされます。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | このストリームのすべてのバッファをクリアし、バッファされたデータを基になるデバイスに書き込ませます。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | 指定されたバイトバッファを埋めるためにバイトを読み取ります。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | 現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | ストリームから1バイトを読み取り、ストリーム内の位置を1バイト進めます。ストリームの末尾に達した場合は -1 を返します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) とストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) とストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | ストリームのすべてのデータを指定されたストリームに保存（コピー）します。ストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | ストリームのデータを指定されたストリームに保存（コピー）します。ストリームの [`Length`](../streamcontainer/length/) の値を使用します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | 現在のストリーム内の位置を設定します。 |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | ストリームの位置をストリームの先頭に設定します。この値は、StreamContainer コンストラクタに渡された開始ストリーム位置からのオフセットを表します。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | ストリームデータを Byte 配列に変換します。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | ストリームデータを Byte 配列に変換します。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | 指定されたすべてのバイトを書き込みます。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | バイトのシーケンスを現在のストリームに書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。 |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | ストリームの現在位置に1バイトを書き込み、ストリーム内の位置を1バイト進めます。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 含まれるデータを別の [`StreamContainer`](../streamcontainer/) にコピーします。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 含まれるデータを別の [`StreamContainer`](../streamcontainer/) にコピーします。 |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | `FileStreamContainer` から Stream への明示的な変換を実行します。（2 つの演算子） |

### 関連項目

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


