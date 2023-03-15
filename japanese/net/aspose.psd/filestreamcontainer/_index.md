---
title: Class FileStreamContainer
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileStreamContainer クラス. ファイル ストリーム処理のヘルパー
type: docs
weight: 4250
url: /ja/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

ファイル ストリーム処理のヘルパー。

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
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | ファイルパスを取得します. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | ストリームが明示的に作成されたかどうかを示す値を取得します。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | このストリームがクローズ時に破棄されるかどうかを示す値を取得します。 |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | ストリームが一時的かどうかを示す値を取得または設定します。 |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | ストリームの長さをバイト単位で取得または設定します。この値はLengthStreamContainer コンストラクターで渡されたストリームの開始位置。 |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | ストリーム内の現在の位置を取得または設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。 |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | データ ストリームを取得します。 |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | 同期されたリソースへのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | 新しいファイル ストリームを作成します。 |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | 既存のファイル ストリームを開きます。ファイル ストリームが存在しない場合は、適切な例外がスローされます。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | このストリームのすべてのバッファをクリアし、バッファリングされたデータが基になるデバイスに書き込まれるようにします. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | バイトを読み取り、指定されたバイト バッファを埋めます。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | 現在のストリームから一連のバイトを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めるか、ストリームの最後にある場合は -1 を返します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | ストリームのデータを指定されたストリームに保存 (コピー) します。デフォルトのバッファサイズを使用[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/)とストリーム[`Length`](../streamcontainer/length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | ストリームのデータを指定されたストリームに保存 (コピー) します。デフォルトのバッファサイズを使用[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/)とストリーム[`Length`](../streamcontainer/length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | ストリームのすべてのデータを指定されたストリームに保存 (コピー) します。ストリームを使用[`Length`](../streamcontainer/length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | ストリームのデータを指定されたストリームに保存 (コピー) します。ストリームを使用[`Length`](../streamcontainer/length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | ストリームのデータを指定されたストリームに保存 (コピー) します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | ストリームのデータを指定されたストリームに保存 (コピー) します。 |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | 現在のストリーム内の位置を設定します。 |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | ストリーム位置をストリームの先頭に設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | ストリーム データをByte配列. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | ストリーム データをByte配列. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | 指定されたすべてのバイトをストリームに書き込みます。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | 現在のストリームに一連のバイトを書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進めます。 |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | ストリーム内の現在の位置に 1 バイトを書き込み、ストリーム内の位置を 1 バイト進めます。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 含まれているデータを別のデータにコピーします[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 含まれているデータを別のデータにコピーします[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | からの明示的な変換を実行します`FileStreamContainer`にStream . (2 operators) |

### 関連項目

* class [StreamContainer](../streamcontainer/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


