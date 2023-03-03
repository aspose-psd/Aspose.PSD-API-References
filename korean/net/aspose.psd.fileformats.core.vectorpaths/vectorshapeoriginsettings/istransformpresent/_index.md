---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: .NET API 참조용 Aspose.PSD
description: VectorShapeOriginSettings 재산. 이 인스턴스에 변환 속성이 있는지 여부를 나타내는 값을 가져옵니다.
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

이 인스턴스에 변환 속성이 있는지 여부를 나타내는 값을 가져옵니다.

```csharp
public bool IsTransformPresent { get; }
```

### 자산 가치

`진실` 이 인스턴스에 transform 속성이 있으면 그렇지 않습니다. 그렇지 않으면,`거짓` .

### 예

다음 코드는 벡터 경로가 포함된 모양 레이어의 크기를 조정하는 기능을 보여줍니다.

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또한보십시오

* class [VectorShapeOriginSettings](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* 집회 [Aspose.PSD](../../../)


