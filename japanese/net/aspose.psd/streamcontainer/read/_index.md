---
title: StreamContainer.Read
second_title: Aspose.PSD for .NET API リファレンス
description: StreamContainer 方法. バイトを読み取り指定されたバイト バッファを埋めます
type: docs
weight: 110
url: /ja/net/aspose.psd/streamcontainer/read/
---
## Read(byte[]) {#read}

バイトを読み取り、指定されたバイト バッファを埋めます。

```csharp
public virtual int Read(byte[] bytes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| bytes | Byte[] | 埋めるバイト。 |

### 戻り値

読み取られたバイト数。ストリームに十分なバイトがない場合、この値はバッファ内のバイト数よりも少なくなることがあります。

### 関連項目

* class [StreamContainer](../)
* 名前空間 [Aspose.PSD](../../streamcontainer/)
* 組み立て [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

現在のストリームから一連のバイトを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| buffer | Byte[] | バイトの配列。このメソッドが戻ると、バッファには指定されたバイト配列が含まれており、値は*offset*と （*offset* +*count* - 1) 現在のソースから読み取られたバイトに置き換えられます。 |
| offset | Int32 | のゼロベースのバイトオフセット*buffer*現在のストリームから読み取ったデータの格納を開始する位置。 |
| count | Int32 | 現在のストリームから読み取る最大バイト数。 |

### 戻り値

バッファに読み込まれた合計バイト数。要求されたバイト数が現在利用できない場合、これは要求されたバイト数よりも少なくなる可能性があり、ストリームの終わりに達した場合はゼロ (0) になる可能性があります.

### 関連項目

* class [StreamContainer](../)
* 名前空間 [Aspose.PSD](../../streamcontainer/)
* 組み立て [Aspose.PSD](../../../)


