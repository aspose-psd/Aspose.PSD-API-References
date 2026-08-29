---
title: "UnitArrayStructure.UnitArrayStructure"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "UnitArrayStructure 생성자. UnitArrayStructure 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unitarraystructure/
---
{{< psd/tize >}}
## UnitArrayStructure constructor

[`UnitArrayStructure`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public UnitArrayStructure(ClassID keyName, UnitTypes unitType, double[] values)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keyName | ClassID | 키의 이름. |
| unitType | UnitTypes | 단위의 유형입니다. |
| values | Double[] | 값입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 값은 null이면 안 됩니다. |

## 예제

다음 코드는 ObAr 및 UnFl 서명을 지원하는 예를 보여줍니다.

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

### 또 보기

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* enum [UnitTypes](../../unittypes/)
* class [UnitArrayStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


