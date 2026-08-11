---
title: "열거형 ResizeType"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ResizeType 열거형. 리사이즈 유형을 지정합니다."
type: docs
weight: 5870
url: /ko/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

크기 조정 유형을 지정합니다.

```csharp
public enum ResizeType
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 리사이즈 작업 중에 픽셀이 보존되지 않습니다. |
| LeftTopToLeftTop | `1` | 새 이미지의 왼쪽 상단 점이 원본 이미지의 왼쪽 상단 점과 일치합니다. 필요한 경우 잘라내기가 수행됩니다. |
| RightTopToRightTop | `2` | 새 이미지의 오른쪽 상단 점이 원본 이미지의 오른쪽 상단 점과 일치합니다. 필요한 경우 잘라내기가 수행됩니다. |
| RightBottomToRightBottom | `3` | 새 이미지의 오른쪽 하단 점이 원본 이미지의 오른쪽 하단 점과 일치합니다. 필요한 경우 잘라내기가 수행됩니다. |
| LeftBottomToLeftBottom | `4` | 새 이미지의 왼쪽 하단 점이 원본 이미지의 왼쪽 하단 점과 일치합니다. 필요한 경우 잘라내기가 수행됩니다. |
| CenterToCenter | `5` | 새 이미지의 중심이 원본 이미지의 중심과 일치합니다. 필요한 경우 잘라내기가 수행됩니다. |
| LanczosResample | `6` | a=3인 Lanczos 알고리즘을 사용하여 재샘플링합니다. |
| NearestNeighbourResample | `7` | 최근접 이웃 알고리즘을 사용하여 재샘플링합니다. |
| AdaptiveResample | `8` | 가중치와 혼합된 유리 함수 및 lanczos3 보간 알고리즘을 기반으로 하는 적응형 알고리즘을 사용하여 재샘플링합니다. |
| BilinearResample | `9` | 양선형 보간을 사용하여 재샘플링합니다. 필요에 따라 재샘플링 전에 노이즈를 제거하기 위해 이미지 사전 필터링을 허용합니다. |
| HighQualityResample | `10` | 고품질 재샘플링 |
| CatmullRom | `11` | Catmull-Rom 큐빅 보간 방법. |
| CubicConvolution | `12` | Cubic Convolution 보간 방법 |
| CubicBSpline | `13` | CubicBSpline 큐빅 보간 방법 |
| Mitchell | `14` | Mitchell 큐빅 보간 방법 |
| SinC | `15` | Sinc (Lanczos3) 큐빅 보간 방법 |
| Bell | `16` | Bell 보간 방법 |

## 예제

다음 코드는 새로운 SinC 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Bell 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Mitchell 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CatmullRom 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicBSpline 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicConvolution 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


