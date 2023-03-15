---
title: LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API リファレンス
description: LayerResourcesRegistry 方法. ロードLayerResource指定されたものに適した最初に見つかったオープナーを使用するstream .
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

ロード[`LayerResource`](../../layerresource/)指定されたものに適した最初に見つかったオープナーを使用する*stream* .

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ストリーム。 |
| psdVersion | Int32 | PSD版です。 |

### 戻り値

ロードされた[`LayerResource`](../../layerresource/)オープナーが見つからない場合は null.

### 備考

最初のオープナーは、実際には最後に登録されます.

### 関連項目

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* 組み立て [Aspose.PSD](../../../)


