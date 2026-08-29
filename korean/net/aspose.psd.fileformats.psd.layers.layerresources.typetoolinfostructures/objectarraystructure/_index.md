---
title: "ObjectArrayStructure 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.ObjectArrayStructure 클래스. 일반적으로 UnitArrayStructure 배열을 보유하는 ObjectArrayStructure 클래스를 정의합니다. PSD 파일 리소스인 PlLd Resource 및 SoLd Resource에서 사용됩니다."
type: docs
weight: 3590
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
{{< psd/tize >}}
## ObjectArrayStructure class

ObjectArrayStructure 클래스를 정의합니다. 일반적으로 [`UnitArrayStructure`](../unitarraystructure/) 배열을 보유합니다. PSD 파일 리소스, 예를 들어 PlLd Resource 및 SoLd Resource에서 사용됩니다.

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure/#constructor_1)(string, string, OSTypeStructure[]) | 새 `ObjectArrayStructure` 클래스의 인스턴스를 초기화합니다. |
| [ObjectArrayStructure](objectarraystructure/#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | 새 `ObjectArrayStructure` 클래스의 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/) { get; set; } | 객체 배열 클래스 ID를 가져오거나 설정합니다. |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname/) { get; set; } | 객체 배열 클래스 이름을 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key/) { get; } | 객체 배열 구조 키를 가져옵니다. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | 키 이름을 가져오거나 설정합니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length/) { get; } | 바이트 단위의 [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 길이를 가져옵니다. |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount/) { get; } | 객체 배열 하위 구조 개수를 가져옵니다. |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures/) { get; set; } | 구조체 배열의 복사본을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | 헤더 길이를 가져옵니다. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 구조를 지정된 스트림 컨테이너에 저장합니다. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 구조를 지정된 스트림 컨테이너에 저장합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey/) | 'ObAr' 구조 키를 식별합니다. |

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

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


