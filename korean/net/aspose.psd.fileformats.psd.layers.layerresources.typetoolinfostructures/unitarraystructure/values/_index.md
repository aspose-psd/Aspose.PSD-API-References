---
title: "UnitArrayStructure.Values"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "UnitArrayStructure 속성. 단위 배열 구조 값을 가져오거나 설정합니다."
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/
---
{{< psd/tize >}}
## UnitArrayStructure.Values property

단위 배열 구조 값을 가져오거나 설정합니다.

```csharp
public double[] Values { get; set; }
```

### Property Value

단위 배열 구조 값입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | Values 속성은 null이면 안 됩니다. |

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

* class [UnitArrayStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


