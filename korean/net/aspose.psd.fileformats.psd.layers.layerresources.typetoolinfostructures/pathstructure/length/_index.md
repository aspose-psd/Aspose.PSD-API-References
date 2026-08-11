---
title: "PathStructure.Length"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PathStructure 속성. OSTypeStructure 길이를 바이트 단위로 가져옵니다."
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)의 길이를 바이트 단위로 가져옵니다.

```csharp
public override int Length { get; }
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


