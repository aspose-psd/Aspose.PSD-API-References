---
title: "クラス AnimatedDataSectionStructure"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure クラス。アニメーションデータを含むセクションです。"
type: docs
weight: 2510
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
{{< psd/tize >}}
## AnimatedDataSectionStructure class

アニメーションデータを含むセクションです。

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | アニメーションデータ セクション構造体を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | 構造キーを取得します。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | キー名を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | バイト単位で [`OSTypeStructure`](../ostypestructure/) の長さを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | ヘッダーの長さを取得します。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | AnDs の構造キーを識別します。 |

## 例

次のコードは、アニメーション データのタイムライン フレームで遅延時間を設定/更新する方法を示しています。

```csharp
[C#]

string sourceFile = "3_animated.psd";
string outputPsd = "output_3_animated.psd";

T FindStructure<T>(IEnumerable<OSTypeStructure> structures, string keyName) where T : OSTypeStructure
{
    foreach (var structure in structures)
    {
        if (structure.KeyName.ClassName == keyName)
        {
            return structure as T;
        }
    }

    return null;
}

OSTypeStructure[] AddOrReplaceStructure(IEnumerable<OSTypeStructure> structures, OSTypeStructure newStructure)
{
    List<OSTypeStructure> listOfStructures = new List<OSTypeStructure>(structures);

    for (int i = 0; i < listOfStructures.Count; i++)
    {
        OSTypeStructure structure = listOfStructures[i];
        if (structure.KeyName.ClassName == newStructure.KeyName.ClassName)
        {
            listOfStructures.RemoveAt(i);
            break;
        }
    }

    listOfStructures.Add(newStructure);

    return listOfStructures.ToArray();
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var imageResource in image.ImageResources)
    {
        if (imageResource is AnimatedDataSectionResource)
        {
            var animatedData =
                (AnimatedDataSectionStructure) (imageResource as AnimatedDataSectionResource).AnimatedDataSection;
            var framesList = FindStructure<ListStructure>(animatedData.Items, "FrIn");

            var frame1 = (DescriptorStructure)framesList.Types[1];

            // 1 秒に相当する 100 センチ秒のフレーム遅延レコードを作成します。
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### 関連項目

* class [OSTypeStructure](../ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


