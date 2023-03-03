---
title: AnimatedDataSectionResource.AnimatedDataSection
second_title: .NET API 참조용 Aspose.PSD
description: AnimatedDataSectionResource 재산. 애니메이션 데이터 섹션 구조를 가져오거나 설정합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/
---
## AnimatedDataSectionResource.AnimatedDataSection property

애니메이션 데이터 섹션 구조를 가져오거나 설정합니다.

```csharp
public AnimatedDataSectionStructure AnimatedDataSection { get; }
```

### 예

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

            // 1초에 해당하는 100센티초 값으로 프레임 지연 레코드를 생성합니다.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // 시간을 센티초 단위로 설정합니다.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### 또한보십시오

* class [AnimatedDataSectionStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/)
* class [AnimatedDataSectionResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Resources](../../animateddatasectionresource/)
* 집회 [Aspose.PSD](../../../)


