---
title: TextLayer.Resize
second_title: .NET API 참조용 Aspose.PSD
description: TextLayer 방법. 이미지 크기를 조정합니다. 기본값LeftTopToLeftTop사용중입니다.
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

이미지 크기를 조정합니다. 기본값LeftTopToLeftTop사용중입니다.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새 너비입니다. |
| newHeight | Int32 | 새 높이입니다. |
| resizeType | ResizeType | 크기 조정 변환 유형[`ResizeType`](../../../aspose.psd/resizetype/) |

### 예

다음 코드는 크기 조정 메커니즘을 선택하는 매개 변수가 있는 TextLayer.Resize 함수를 보여줍니다.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // 텍스트 레이어의 새로운 크기를 설정합니다.
    const int NewWidth = 250;
    const int NewHeight = 250;

    // 크기 조정 기능이 레이어 크기를 조정하는 방법에 대한 메커니즘을 설정합니다(기본값).
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // 여기를 사용하여 텍스트 레이어의 크기를 조정하는 새로운 메커니즘
    // 레이어뿐만 아니라 텍스트 레이어의 변환 행렬도 변경됩니다.
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // 델타의 이유는 다른 기본 글꼴입니다.
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // 다 괜찮아
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### 또한보십시오

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* 집회 [Aspose.PSD](../../../)


