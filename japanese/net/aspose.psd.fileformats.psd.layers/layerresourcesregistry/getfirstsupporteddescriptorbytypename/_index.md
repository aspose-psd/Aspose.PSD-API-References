---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptorByTypeName"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerResourcesRegistry メソッド。型名で最初にサポートされる記述子を取得します。"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptorByTypeName method

タイプ名で最初にサポートされている記述子を取得します。

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptorByTypeName(string descriptorTypeName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| descriptorTypeName | 文字列 | 記述子の型名です。 |

### 戻り値

最初に見つかったオープナー記述子、またはそのような記述子が見つからない場合は null。

## 備考

最初のオープナー記述子は実際には最後に登録されたものになります。

### 関連項目

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


