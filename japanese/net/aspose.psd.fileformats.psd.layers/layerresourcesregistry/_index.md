---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry クラス. PSD ファイルをロードするためのレイヤ リソース レジストリを定義します
type: docs
weight: 3390
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

PSD ファイルをロードするためのレイヤ リソース レジストリを定義します。

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
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | サポートされている最初のオープナー記述子を取得します。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | 型名でサポートされている最初の記述子を取得します。 |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | ロード[`LayerResource`](../layerresource/)指定されたものに適した最初に見つかったオープナーを使用する*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | オープナーを登録します。 |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | オープナーの登録を解除します。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 組み立て [Aspose.PSD](../../)


