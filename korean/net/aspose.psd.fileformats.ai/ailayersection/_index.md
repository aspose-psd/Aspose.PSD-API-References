---
title: Class AiLayerSection
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Ai.AiLayerSection 수업. Ai 형식 레이어 Section
type: docs
weight: 1270
url: /ko/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

Ai 형식 레이어 Section

```csharp
public sealed class AiLayerSection : AiDataSection
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | 파란색 구성 요소를 가져오거나 설정합니다. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | 색상 번호를 가져오거나 설정합니다. -1은 Red, Green, Blue 속성의 사용자 정의 색상 값입니다. 레이어의 색상 설정을 지정합니다. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | 희미한 값을 백분율로 가져오거나 설정합니다. 레이어에 포함된 연결된 이미지 및 비트맵 이미지의 강도를 지정된 백분율로 줄입니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | 녹색 구성 요소를 가져오거나 설정합니다. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | 이 레이어가 흐리게 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. 레이어에 포함된 연결된 이미지와 비트맵 이미지의 강도를 줄입니다. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | 이 레이어가 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. 항목에 대한 변경을 방지합니다. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | 이 레이어가 미리보기인지 여부를 나타내는 값을 가져오거나 설정합니다. 레이어에 포함된 아트웍을 윤곽선 대신 컬러로 표시합니다. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | 이 레이어가 인쇄되는지 여부를 나타내는 값을 가져오거나 설정합니다. true인 경우 레이어에 포함된 아트웍을 인쇄 가능하게 만듭니다. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | 이 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. true인 경우 아트보드의 레이어에 포함된 모든 아트워크를 표시합니다. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | 이 레이어가 템플릿 레이어인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | 레이어 이름을 가져오거나 설정합니다. 레이어 패널에 나타나는 항목의 이름을 지정합니다. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | 래스터 이미지를 가져옵니다. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | 빨간색 구성 요소를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | 래스터 이미지를 추가합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | 문자열 데이터를 가져옵니다. |

### 예

다음 코드는 AI 형식 파일에서 래스터 이미지 설정을 로드하는 방법을 보여줍니다.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### 또한보십시오

* class [AiDataSection](../aidatasection/)
* 네임스페이스 [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* 집회 [Aspose.PSD](../../)


