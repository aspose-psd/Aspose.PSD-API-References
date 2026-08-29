---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerResourcesRegistry メソッド。最初にサポートされるオープナー記述子を取得します。"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

最初にサポートされているオープナー記述子を取得します。

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ストリームです。 |
| psdVersion | Int32 | PSD バージョンです。 |

### 戻り値

レイヤーリソースローダー記述子、またはそのようなストリームに対してローダー記述子がサポートされていない場合は null。

## 備考

最初のローダーは実際には最後に登録されたものになります。

### 関連項目

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


