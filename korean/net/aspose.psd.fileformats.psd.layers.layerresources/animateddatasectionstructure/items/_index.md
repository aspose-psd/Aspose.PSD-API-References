---
title: "AnimatedDataSectionStructure.Items"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "AnimatedDataSectionStructure 속성. 애니메이션 데이터 섹션 구조를 가져오거나 설정합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/
---
{{< psd/tize >}}
## AnimatedDataSectionStructure.Items property

애니메이션 데이터 섹션 구조를 가져오거나 설정합니다.

```csharp
public OSTypeStructure[] Items { get; }
```

## 예제

다음 코드는 애니메이션 데이터의 타임라인 프레임에서 지연 시간을 설정/업데이트하는 방법을 보여줍니다.

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

            // 1초에 해당하는 100센티초 값을 가진 프레임 지연 레코드를 생성합니다.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### 또 보기

* class [OSTypeStructure](../../ostypestructure/)
* class [AnimatedDataSectionStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


