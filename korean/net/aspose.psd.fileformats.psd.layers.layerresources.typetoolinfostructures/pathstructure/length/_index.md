---
title: PathStructure.Length
second_title: .NET API 참조용 Aspose.PSD
description: PathStructure 재산. 가져오기OSTypeStructure 바이트 길이.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

가져오기[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 바이트 길이.

```csharp
public override int Length { get; }
```

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


