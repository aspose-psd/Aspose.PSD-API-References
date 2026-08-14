---
title: "IRasterImageRawDataLoader クラス"
type: docs
weight: 2020
url: /ja/python-net/aspose.psd/irasterimagerawdataloader/
---

**Summary:** The raster image raw data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | 生データのロードがサポートされているかどうかを示す値を取得します。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 現在の生データ設定を取得します。これらの設定を使用する場合、データは変換なしでロードされることに注意してください。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1) | 生データをロードします。 |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

生データをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 生データを読み込む矩形。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 読み込まれたデータに使用する生データ設定です。データが指定された形式でない場合、データ変換が実行されます。 |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 生データローダー。 |

