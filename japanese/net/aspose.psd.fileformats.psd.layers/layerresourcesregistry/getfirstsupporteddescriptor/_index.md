---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API リファレンス
description: LayerResourcesRegistry 方法. サポートされている最初のオープナー記述子を取得します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

サポートされている最初のオープナー記述子を取得します。

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ストリーム。 |
| psdVersion | Int32 | PSD版です。 |

### 戻り値

レイヤー リソース ローダー記述子、またはそのようなストリームでローダー記述子がサポートされていない場合は null.

### 備考

最初のローダーは実際には最後に登録されたものになります.

### 関連項目

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* 組み立て [Aspose.PSD](../../../)


