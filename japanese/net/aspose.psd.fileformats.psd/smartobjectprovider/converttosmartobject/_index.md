---
title: "SmartObjectProvider.ConvertToSmartObject"
second_title: "Aspose.PSD for .NET API Reference"
description: "SmartObjectProvider メソッド。レイヤーを埋め込みスマートオブジェクトに変換します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd/smartobjectprovider/converttosmartobject/
---
{{< psd/tize >}}
## ConvertToSmartObject(params int[]) {#converttosmartobject_1}

レイヤーを埋め込みスマートオブジェクトに変換します。

```csharp
public SmartObjectLayer ConvertToSmartObject(params int[] layerNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layerNumbers | Int32[] | レイヤー番号です。 |

### 戻り値

作成された [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) インスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 変換するレイヤーがありません。またはレイヤー番号が範囲外です。 |

### 関連項目

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## ConvertToSmartObject(Layer[]) {#converttosmartobject}

レイヤーを埋め込みスマートオブジェクトに変換します。

```csharp
public SmartObjectLayer ConvertToSmartObject(Layer[] layers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layers | Layer[] | レイヤーです。 |

### 戻り値

作成された [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) インスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 変換するレイヤーがありません。 |

### 関連項目

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


