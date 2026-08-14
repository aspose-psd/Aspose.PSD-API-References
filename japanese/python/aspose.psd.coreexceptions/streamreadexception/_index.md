---
title: "StreamReadException クラス"
type: docs
weight: 240
url: /ja/python-net/aspose.psd.coreexceptions/streamreadexception/
---

**Summary:** The stream reading exception. Caused when stream reading failed due to incorrect offset and bytes count request.

**Module:** [aspose.psd.coreexceptions](/psd/python-net/aspose.psd.coreexceptions/)

**Full Name:** aspose.psd.coreexceptions.StreamReadException

**Inheritance:** FrameworkException

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [StreamReadException(message)](#StreamReadException_message_1) | 新しい [StreamReadException](/psd/python-net/aspose.psd.coreexceptions/streamreadexception/) クラスのインスタンスを初期化します。 |
| [StreamReadException(message, expected_read_count, actual_read_count)](#StreamReadException_message_expected_read_count_actual_read_count_2) | 新しい [StreamReadException](/psd/python-net/aspose.psd.coreexceptions/streamreadexception/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| actual_read_count | int | r | 実際の読み取りバイト数を取得します。 |
| expected_read_count | int | r | 期待される読み取りバイト数を取得します。 |


### Constructor: StreamReadException(message) {#StreamReadException_message_1}


```
 StreamReadException(message) 
```

新しい [StreamReadException](/psd/python-net/aspose.psd.coreexceptions/streamreadexception/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| メッセージ | string | メッセージ。 |

### Constructor: StreamReadException(message, expected_read_count, actual_read_count) {#StreamReadException_message_expected_read_count_actual_read_count_2}


```
 StreamReadException(message, expected_read_count, actual_read_count) 
```

新しい [StreamReadException](/psd/python-net/aspose.psd.coreexceptions/streamreadexception/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| メッセージ | string | メッセージ。 |
| expected_read_count | int | 期待される読み取りカウント。 |
| actual_read_count | int | 実際の読み取りカウント。 |

