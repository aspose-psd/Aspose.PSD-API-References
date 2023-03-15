---
title: PathStructure.Path
second_title: .NET API 참조용 Aspose.PSD
description: PathStructure 재산. 경로를 가져오거나 설정합니다.
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

경로를 가져오거나 설정합니다.

```csharp
public string Path { get; set; }
```

### 자산 가치

전체 경로입니다.

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

* class [PathStructure](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* 집회 [Aspose.PSD](../../../)


