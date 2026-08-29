---
title: "ObjectArrayStructure.ObjectArrayStructure"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ObjectArrayStructure 생성자. ObjectArrayStructure 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/objectarraystructure/
---
{{< psd/tize >}}
## ObjectArrayStructure(string, string, OSTypeStructure[]) {#constructor_1}

[`ObjectArrayStructure`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ObjectArrayStructure(string keyName, string classIdName, OSTypeStructure[] structures)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keyName | String | 키의 이름. |
| classIdName | String | 클래스 식별자의 이름. |
| 구조 | OSTypeStructure[] | 구조들. |

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

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [ObjectArrayStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)

---

## ObjectArrayStructure(int, ClassID, ClassID, string, OSTypeStructure[]) {#constructor}

[`ObjectArrayStructure`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ObjectArrayStructure(int key, ClassID keyName, ClassID classID, string className, 
    OSTypeStructure[] structures)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | Int32 | 정수 키. |
| keyName | ClassID | 키 이름입니다. |
| classID | ClassID | 클래스 식별자. |
| className | String | 클래스의 이름. |
| 구조 | OSTypeStructure[] | 구조들. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | classID가 null입니다 |

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
* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [ObjectArrayStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


