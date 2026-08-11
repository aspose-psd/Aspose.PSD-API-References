---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PathStructure 생성자. PathStructure 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

[`PathStructure`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public PathStructure(ClassID keyName)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keyName | ClassID | 키 이름입니다. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


