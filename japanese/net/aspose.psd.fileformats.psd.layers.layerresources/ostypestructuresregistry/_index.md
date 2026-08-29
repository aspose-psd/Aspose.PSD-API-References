---
title: "クラス OSTypeStructuresRegistry"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry クラス。OSTypeStructure リソースレジストリを表します。"
type: docs
weight: 3200
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

[`OSTypeStructure`](../ostypestructure/) リソースレジストリを表します。

```csharp
public static class OSTypeStructuresRegistry
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | 登録された記述子を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | 最初にサポートされているオープナー記述子を取得します。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | タイプ名で最初にサポートされている記述子を取得します。 |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | 指定された *stream* に適した最初に見つかったオープナーを使用して [`OSTypeStructure`](../ostypestructure/) をロードします。 |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | オープナーを登録します。 |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | オープナーの登録を解除します。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


