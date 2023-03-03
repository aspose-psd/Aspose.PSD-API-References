---
title: Class OSTypeStructuresRegistry
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry クラス. はOSTypeStructureリソースレジストリ.
type: docs
weight: 2860
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
## OSTypeStructuresRegistry class

は[`OSTypeStructure`](../ostypestructure/)リソースレジストリ.

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
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | サポートされている最初のオープナー記述子を取得します。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | 型名でサポートされている最初の記述子を取得します。 |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | ロード[`OSTypeStructure`](../ostypestructure/)指定されたものに適した最初に見つかったオープナーを使用する*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | オープナーを登録します。 |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | オープナーの登録を解除します。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


