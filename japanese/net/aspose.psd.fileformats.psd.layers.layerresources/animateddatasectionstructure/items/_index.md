---
title: AnimatedDataSectionStructure.Items
second_title: Aspose.PSD for .NET API リファレンス
description: AnimatedDataSectionStructure 財産. アニメーション データ セクション構造を取得または設定します
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/
---
## AnimatedDataSectionStructure.Items property

アニメーション データ セクション構造を取得または設定します。

```csharp
public OSTypeStructure[] Items { get; }
```

### 例

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

            // 1 秒に等しい値 100 センチ秒のフレーム遅延レコードを作成します。
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // 時間をセンチ秒単位で設定します。

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### 関連項目

* class [OSTypeStructure](../../ostypestructure/)
* class [AnimatedDataSectionStructure](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../animateddatasectionstructure/)
* 組み立て [Aspose.PSD](../../../)


