---
title: "SplitStreamContainer.Read"
second_title: "Aspose.PSD for .NET API Reference"
description: "SplitStreamContainer メソッド。指定されたバイトバッファを埋めるためにバイトを読み取ります。"
type: docs
weight: 110
url: /ja/net/aspose.psd/splitstreamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

指定されたバイトバッファを埋めるためにバイトを読み取ります。

```csharp
public override int Read(byte[] bytes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バイト | Byte[] | 埋めるバイト。 |

### 戻り値

読み取られたバイト数。ストリームに十分なバイトがない場合、この値はバッファ内のバイト数より少なくなることがあります。

### 関連項目

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | Byte[] | バイト配列。このメソッドが返ると、バッファは指定されたバイト配列を含み、*offset* から (*offset* + *count* - 1) までの値が現在のソースから読み取られたバイトで置き換えられます。 |
| offset | Int32 | 現在のストリームから読み取ったデータの格納を開始する *buffer* 内のゼロベースのバイトオフセットです。 |
| カウント | Int32 | 現在のストリームから読み取る最大バイト数です。 |

### 戻り値

バッファに読み込まれたバイトの総数です。要求されたバイト数が現在利用できない場合は要求バイト数未満になることがあります。また、ストリームの終端に達した場合はゼロ (0) になります。

### 関連項目

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


