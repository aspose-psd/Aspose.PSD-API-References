---
title: "IPartialRawDataLoader クラス"
type: docs
weight: 1940
url: /ja/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | ロードされたデータを処理します。 |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | ロードされたデータを処理します。 |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

ロードされたデータを処理します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | データ矩形です。 |
| data | byte | 生データ。 |
| start | [Point](/psd/python-net/aspose.psd/point) | 開始データポイントです。 (left,top) と等しくない場合、完全な長方形ではありません。 |
| end | [Point](/psd/python-net/aspose.psd/point) | 終了データポイントです。 (right,bottom) と等しくない場合、完全な長方形ではありません。 |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

ロードされたデータを処理します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | データ矩形です。 |
| data | byte | 生データ。 |
| start | [Point](/psd/python-net/aspose.psd/point) | 開始データポイントです。 (left,top) と等しくない場合、完全な長方形ではありません。 |
| end | [Point](/psd/python-net/aspose.psd/point) | 終了データポイントです。 (right,bottom) と等しくない場合、完全な長方形ではありません。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | ロードオプション。 |

