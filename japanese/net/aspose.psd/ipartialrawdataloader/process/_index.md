---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.PSD for .NET API Reference"
description: "IPartialRawDataLoader メソッド。ロードされたデータを処理します"
type: docs
weight: 10
url: /ja/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

ロードされたデータを処理します。

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 矩形 | Rectangle | データの矩形。 |
| データ | Byte[] | 生データ。 |
| 開始 | Point | 開始データポイント。 (left,top) と等しくない場合、完全な矩形ではありません。 |
| 終了 | Point | 終了データポイント。 (right,bottom) と等しくない場合、完全な矩形ではありません。 |

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

ロードされたデータを処理します。

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 矩形 | Rectangle | データの矩形。 |
| データ | Byte[] | 生データ。 |
| 開始 | Point | 開始データポイント。 (left,top) と等しくない場合、完全な矩形ではありません。 |
| 終了 | Point | 終了データポイント。 (right,bottom) と等しくない場合、完全な矩形ではありません。 |
| loadOptions | LoadOptions | ロードオプション。 |

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


