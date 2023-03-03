---
title: Class DataStreamSupporter
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.DataStreamSupporter クラス. データ ストリーム コンテナー
type: docs
weight: 740
url: /ja/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

データ ストリーム コンテナー。

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータ ストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要かどうかを示す値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基盤から追加のデータ読み込みが実行されないようにします[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | オブジェクトのデータを現在の`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | オブジェクトのデータを指定されたファイルの場所に保存します。 |

### 関連項目

* class [DisposableObject](../disposableobject/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


