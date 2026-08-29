---
title: "クラス DataStreamSupporter"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.DataStreamSupporter クラス。データ ストリーム コンテナ"
type: docs
weight: 750
url: /ja/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

データストリームコンテナ。

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データ読み取りが不要であるかどうかを示す値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基礎となる [`DataStreamContainer`](./datastreamcontainer/) から追加のデータ読み込みが行われないことを保証します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | オブジェクトのデータを現在の `DataStreamSupporter` に保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | オブジェクトのデータを指定されたファイル位置に保存します。 |

### 関連項目

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


