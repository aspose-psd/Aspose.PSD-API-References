---
title: "VectorShapeOriginSettings.IsTransformPresent"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VectorShapeOriginSettings 속성. 이 인스턴스에 변환 속성이 있는지 여부를 나타내는 값을 가져옵니다"
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsTransformPresent property

이 인스턴스에 변환 속성이 있는지 여부를 나타내는 값을 가져옵니다.

```csharp
public bool IsTransformPresent { get; }
```

### Property Value

`true` 이 인스턴스에 변환 속성이 있는 경우; 그렇지 않으면 `false`.

## 예제

다음 코드는 벡터 경로를 포함하는 쉐이프 레이어의 크기를 조정하는 기능을 보여줍니다.

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

### 또 보기

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


