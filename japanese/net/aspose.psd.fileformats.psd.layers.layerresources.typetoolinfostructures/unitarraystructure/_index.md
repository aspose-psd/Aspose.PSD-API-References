---
title: Class UnitArrayStructure
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.UnitArrayStructure クラス. を保持する UnitArrayStructure クラスを定義しますDouble値配列とその測定単位. PSD ファイル リソースで使用されますObjectArrayStructure .
type: docs
weight: 3270
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---
## UnitArrayStructure class

を保持する UnitArrayStructure クラスを定義します。Double値配列とその測定単位. PSD ファイル リソースで使用されます。[`ObjectArrayStructure`](../objectarraystructure/) .

```csharp
public sealed class UnitArrayStructure : OSTypeStructure
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [UnitArrayStructure](unitarraystructure/)(ClassID, UnitTypes, double[]) | の新しいインスタンスを初期化します`UnitArrayStructure`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/key/) { get; } | このユニット配列構造体キーを取得します。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | キー名を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/length/) { get; } | を取得します[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)バイト単位の長さ. |
| [UnitType](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unittype/) { get; set; } | の測定単位タイプを取得または設定します`UnitArrayStructure`値. |
| [ValueCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/valuecount/) { get; } | 値のカウントを取得します。 |
| [Values](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/) { get; set; } | ユニット配列構造体の値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | ヘッダー長を取得します。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 指定したストリーム コンテナーに構造体を保存します。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 指定したストリーム コンテナーに構造体を保存します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/structurekey/) | は「UnFl」を定義します`UnitArrayStructure`key. |

### 例

次のコードは、ObAr および UnFl 署名のサポートを示しています。

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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* 組み立て [Aspose.PSD](../../)


