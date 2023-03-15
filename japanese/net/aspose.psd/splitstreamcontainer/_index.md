---
title: Class SplitStreamContainer
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.SplitStreamContainer クラス. ストリームを含みストリーム処理ルーチンを提供する分割ストリーム コンテナーを表します
type: docs
weight: 5630
url: /ja/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

ストリームを含み、ストリーム処理ルーチンを提供する分割ストリーム コンテナーを表します。

```csharp
public class SplitStreamContainer : StreamContainer
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | の新しいインスタンスを初期化します`SplitStreamContainer`class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | の新しいインスタンスを初期化します`SplitStreamContainer`class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | の新しいインスタンスを初期化します`SplitStreamContainer`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | ストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | ストリームがシークをサポートしているかどうかを示す値を取得します。 |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | ストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | このストリームがクローズ時に破棄されるかどうかを示す値を取得します。 |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | ストリームの長さをバイト単位で取得または設定します。この値はLengthStreamContainer コンストラクターで渡されたストリームの開始位置。 |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | ストリーム内の現在の位置を取得または設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。 |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | データ ストリームを取得します。 |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | 同期されたリソースへのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | このストリームのすべてのバッファをクリアし、バッファリングされたデータが基になるデバイスに書き込まれるようにします. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | ストリーム コンテナーを指定された位置に挿入します。 |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | バイトを読み取り、指定されたバイト バッファを埋めます。 |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | 現在のストリームから一連のバイトを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めるか、ストリームの最後にある場合は -1 を返します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | ストリームのデータを指定されたストリームに保存 (コピー) します。デフォルトのバッファサイズを使用[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/)とストリーム[`Length`](../streamcontainer/length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | ストリームのデータを指定されたストリームに保存 (コピー) します。デフォルトのバッファサイズを使用[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/)とストリーム[`Length`](../streamcontainer/length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | ストリームのすべてのデータを指定されたストリームに保存 (コピー) します。ストリームを使用[`Length`](../streamcontainer/length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | ストリームのデータを指定されたストリームに保存 (コピー) します。ストリームを使用[`Length`](../streamcontainer/length/)値. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | ストリームのデータを指定されたストリームに保存 (コピー) します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | ストリームのデータを指定されたストリームに保存 (コピー) します。 |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | 現在のストリーム内の位置を設定します。 |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | ストリーム位置をストリームの先頭に設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。 |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | ストリーム データをByte配列. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | ストリーム データをByte配列. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | 指定されたすべてのバイトをストリームに書き込みます。 |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | 現在のストリームに一連のバイトを書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進めます。 |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | ストリーム内の現在の位置に 1 バイトを書き込み、ストリーム内の位置を 1 バイト進めます。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 含まれているデータを別のデータにコピーします[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 含まれているデータを別のデータにコピーします[`StreamContainer`](../streamcontainer/) . |

### 関連項目

* class [StreamContainer](../streamcontainer/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


