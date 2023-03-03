---
title: PathStructure.PathStructure
second_title: .NET API 참조용 Aspose.PSD
description: PathStructure 건설자. 의 새 인스턴스를 초기화합니다.PathStructure 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

의 새 인스턴스를 초기화합니다.[`PathStructure`](../) 클래스.

```csharp
public PathStructure(ClassID keyName)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| keyName | ClassID | 키 이름입니다. |

### 예

다음 코드는 PathStructure 구조로 파일을 로드하는 기능을 보여줍니다.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### 또한보십시오

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* 집회 [Aspose.PSD](../../../)


