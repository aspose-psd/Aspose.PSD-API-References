---
title: "DataStreamSupporter クラス"
type: docs
weight: 1030
url: /ja/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | オブジェクトのデータストリームを取得します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| is_cached | bool | r | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| cache_data() | データをキャッシュし、基になる [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) から追加のデータ読み込みが行われないことを保証します。 |
| save() | オブジェクトのデータを現在の [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) に保存します。 |
| [save(file_path)](#save_file_path_1) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, over_write)](#save_file_path_over_write_2) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(stream)](#save_stream_3) | オブジェクトのデータを指定されたストリームに保存します。 |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |
| over_write | bool | もし <c>true</c> に設定するとファイル内容を上書きし、そうでなければ追記が行われます。 |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | オブジェクトのデータを保存するストリーム。 |

