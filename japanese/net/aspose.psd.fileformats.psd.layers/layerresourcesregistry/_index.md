---
title: "クラス LayerResourcesRegistry"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry クラス。PSD ファイルの読み込み用レイヤーリソースレジストリを定義します"
type: docs
weight: 3790
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

PSDファイルの読み込み用レイヤーリソースレジストリを定義します。

```csharp
public static class LayerResourcesRegistry
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | 登録された記述子を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | 最初にサポートされているオープナー記述子を取得します。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | タイプ名で最初にサポートされている記述子を取得します。 |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | 指定された *stream* に適した最初に見つかったオープナーを使用して [`LayerResource`](../layerresource/) をロードします。 |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | オープナーを登録します。 |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | オープナーの登録を解除します。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


