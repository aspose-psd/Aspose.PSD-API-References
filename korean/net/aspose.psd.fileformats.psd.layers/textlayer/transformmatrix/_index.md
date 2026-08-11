---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "TextLayer property. 변환 행렬을 가져오거나 설정합니다"
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

변환 행렬을 가져오거나 설정합니다.

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

변환 행렬

## 예제

다음 코드는 텍스트 레이어의 모든 텍스트 부분에 대한 폰트 크기를 가져오는 방법을 보여줍니다.

```csharp
[C#]

// 잘못된 폰트 크기가 추출되었습니다 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // 이전 API(첫 번째 단락 폰트 사용)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // 기본 폰트 크기 확인 중
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 실제 폰트 크기 확인 중
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // 새 API(하나의 텍스트 레이어에 다양한 폰트 크기가 포함될 수 있음)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // 기본 부분 폰트 크기 확인 중
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 실제 부분 폰트 크기 확인 중
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### 또 보기

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


