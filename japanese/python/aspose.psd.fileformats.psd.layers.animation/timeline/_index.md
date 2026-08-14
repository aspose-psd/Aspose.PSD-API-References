---
title: "Timeline クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Timeline()](#Timeline__1) | Timeline クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| active_frame_index | int | r | アクティブフレームのインデックスを取得します。 |
| af_st | int | r/w | AFSt 値を取得または設定します。 |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | フレームのリストを取得します。 |
| fs_id | int | r/w | FsID 値を取得または設定します。 |
| loopes_count | ushort | r/w | ループ数を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | 保存オプションに従って、指定された形式で PsdImage と Timeline のデータを指定されたファイル位置に保存します。 |
| [save(output_stream, options)](#save_output_stream_options_2) | 保存オプションに従って、指定された形式で PsdImage と Timeline のデータを指定されたストリームに保存します。 |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | アクティブフレームを対象フレームに切り替えます。 |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Timeline クラスの新しいインスタンスを初期化します

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

保存オプションに従って、指定された形式で PsdImage と Timeline のデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

保存オプションに従って、指定された形式で PsdImage と Timeline のデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | 出力ストリームです。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

アクティブフレームを対象フレームに切り替えます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| target_active_frame_index | int | 対象フレームのインデックスです。 |

