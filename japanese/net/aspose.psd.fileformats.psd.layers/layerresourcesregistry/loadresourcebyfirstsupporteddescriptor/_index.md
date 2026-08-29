---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerResourcesRegistry メソッド。指定されたストリームに適した最初に見つかったオープナーを使用して LayerResource をロードします。"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

指定された *stream* に適した最初に見つかったオープナーを使用して [`LayerResource`](../../layerresource/) をロードします。

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ストリームです。 |
| psdVersion | Int32 | PSD バージョンです。 |

### 戻り値

ロードされた [`LayerResource`](../../layerresource/)、またはオープナーが見つからない場合は null。

## 備考

最初のオープナーは実際には最後に登録されたものになります。

### 関連項目

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


