---
title: "PathStructure.StructureKey"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PathStructure 필드. 구조 키를 식별합니다."
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
{{< psd/tize >}}
## PathStructure.StructureKey field

구조 키를 식별합니다.

```csharp
public const int StructureKey;
```

## 예제

다음 코드는 PathStructure 구조를 사용하여 파일을 로드하는 기능을 보여줍니다.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### 또 보기

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


