---
title: "ObjectArrayStructure クラス"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.ObjectArrayStructure クラス。 通常 UnitArrayStructure 配列を保持する ObjectArrayStructure クラスを定義します。 PlLd リソースや SoLd リソースなどの PSD ファイルリソースで使用されます。"
type: docs
weight: 3590
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
{{< psd/tize >}}
## ObjectArrayStructure class

ObjectArrayStructure クラスを定義します。このクラスは通常 [`UnitArrayStructure`](../unitarraystructure/) 配列を保持します。 PlLd リソースや SoLd リソースなどの PSD ファイルリソースで使用されます。

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure/#constructor_1)(string, string, OSTypeStructure[]) | `ObjectArrayStructure` クラスの新しいインスタンスを初期化します。 |
| [ObjectArrayStructure](objectarraystructure/#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | `ObjectArrayStructure` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/) { get; set; } | オブジェクト配列クラス ID を取得または設定します。 |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname/) { get; set; } | オブジェクト配列クラス名を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key/) { get; } | オブジェクト配列構造キーを取得します。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | キー名を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length/) { get; } | バイト単位で[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) の長さを取得します。 |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount/) { get; } | オブジェクト配列サブ構造の数を取得します。 |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures/) { get; set; } | 構造体配列のコピーを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | ヘッダーの長さを取得します。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey/) | 'ObAr' 構造キーを識別します。 |

## 例

次のコードは ObAr と UnFl のシグネチャのサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### 関連項目

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


