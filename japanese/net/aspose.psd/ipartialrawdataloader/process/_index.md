---
title: IPartialRawDataLoader.Process
second_title: Aspose.PSD for .NET API リファレンス
description: IPartialRawDataLoader 方法. 読み込んだデータを処理します
type: docs
weight: 10
url: /ja/net/aspose.psd/ipartialrawdataloader/process/
---
## Process(Rectangle, byte[], Point, Point) {#process}

読み込んだデータを処理します。

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rectangle | Rectangle | データ四角形。 |
| data | Byte[] | 生データ。 |
| start | Point | 開始データ ポイント。 (left,top) と等しくない場合は、完全な長方形ではないことを意味します。 |
| end | Point | 終了データ ポイント。 (right,bottom) と等しくない場合は、完全な長方形ではないことを意味します。 |

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* 名前空間 [Aspose.PSD](../../ipartialrawdataloader/)
* 組み立て [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

読み込んだデータを処理します。

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rectangle | Rectangle | データ四角形。 |
| data | Byte[] | 生データ。 |
| start | Point | 開始データ ポイント。 (left,top) と等しくない場合は、完全な長方形ではないことを意味します。 |
| end | Point | 終了データ ポイント。 (right,bottom) と等しくない場合は、完全な長方形ではないことを意味します。 |
| loadOptions | LoadOptions | 読み込みオプション。 |

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* 名前空間 [Aspose.PSD](../../ipartialrawdataloader/)
* 組み立て [Aspose.PSD](../../../)


