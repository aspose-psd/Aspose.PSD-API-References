---
title: Class StreamContainer
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.StreamContainer クラス. ストリームを含みストリーム処理ルーチンを提供するストリーム コンテナーを表します
type: docs
weight: 5640
url: /ja/net/aspose.psd/streamcontainer/
---
## StreamContainer class

ストリームを含み、ストリーム処理ルーチンを提供するストリーム コンテナーを表します。

```csharp
public class StreamContainer : DisposableObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | の新しいインスタンスを初期化します`StreamContainer`class. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | の新しいインスタンスを初期化します`StreamContainer`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | ストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | ストリームがシークをサポートしているかどうかを示す値を取得します。 |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | ストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | このストリームがクローズ時に破棄されるかどうかを示す値を取得します。 |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | ストリームの長さをバイト単位で取得または設定します。この値はLengthStreamContainer コンストラクターで渡されたストリームの開始位置。 |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | ストリーム内の現在の位置を取得または設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。 |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | データ ストリームを取得します。 |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | 同期されたリソースへのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | このストリームのすべてのバッファをクリアし、バッファリングされたデータが基になるデバイスに書き込まれるようにします. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | バイトを読み取り、指定されたバイト バッファを埋めます。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | 現在のストリームから一連のバイトを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めるか、ストリームの最後にある場合は -1 を返します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | ストリームのデータを指定されたストリームに保存 (コピー) します。デフォルトのバッファサイズを使用[`ReadWriteBytesCount`](./readwritebytescount/)とストリーム[`Length`](./length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | ストリームのデータを指定されたストリームに保存 (コピー) します。デフォルトのバッファサイズを使用[`ReadWriteBytesCount`](./readwritebytescount/)とストリーム[`Length`](./length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | ストリームのすべてのデータを指定されたストリームに保存 (コピー) します。ストリームを使用[`Length`](./length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | ストリームのデータを指定されたストリームに保存 (コピー) します。ストリームを使用[`Length`](./length/)値. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | ストリームのデータを指定されたストリームに保存 (コピー) します。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | ストリームのデータを指定されたストリームに保存 (コピー) します。 |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | 現在のストリーム内の位置を設定します。 |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | ストリーム位置をストリームの先頭に設定します。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | ストリーム データをByte配列. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | ストリーム データをByte配列. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | 指定されたすべてのバイトをストリームに書き込みます。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | 現在のストリームに一連のバイトを書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進めます。 |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | ストリーム内の現在の位置に 1 バイトを書き込み、ストリーム内の位置を 1 バイト進めます。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | 含まれているデータを別のデータにコピーします`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | 含まれているデータを別のデータにコピーします`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | からの明示的な変換を実行します`StreamContainer`にStream . |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | 順次読み取り時の読み取りおよび書き込みバイト数を指定します。 |

### 関連項目

* class [DisposableObject](../disposableobject/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


