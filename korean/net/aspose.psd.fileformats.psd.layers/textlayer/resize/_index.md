---
title: "TextLayer.Resize"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "TextLayer method. 이미지를 크기 조정합니다. 기본 LeftTopToLeftTop이 사용됩니다"
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

이미지를 크기 조정합니다. 기본 LeftTopToLeftTop이 사용됩니다.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새로운 너비. |
| newHeight | Int32 | 새로운 높이. |
| resizeType | ResizeType | 리사이즈 변환 유형 [`ResizeType`](../../../aspose.psd/resizetype/) |

## 예제

다음 코드는 TextLayer.Resize 함수를 보여주며, 리사이즈 메커니즘을 선택하는 매개변수를 사용합니다.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // 텍스트 레이어의 새 크기를 설정합니다
    const int NewWidth = 250;
    const int NewHeight = 250;

    // 리사이즈 함수가 레이어를 어떻게 크기 조정할지에 대한 메커니즘을 설정합니다 (기본값)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // 여기에서 사용되는 텍스트 레이어의 새로운 리사이즈 메커니즘
    // 레이어뿐만 아니라 텍스트 레이어의 변환 행렬도 변경됩니다
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // 델타의 이유는 기본 글꼴이 다르기 때문입니다
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // 모두 정상입니다
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### 또 보기

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


