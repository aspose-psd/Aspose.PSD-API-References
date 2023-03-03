---
title: Enum ResizeType
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ResizeType 열거형. 크기 조정 유형을 지정합니다.
type: docs
weight: 5370
url: /ko/net/aspose.psd/resizetype/
---
## ResizeType enumeration

크기 조정 유형을 지정합니다.

```csharp
public enum ResizeType
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 크기 조정 작업 중에 픽셀이 보존되지 않습니다. |
| LeftTopToLeftTop | `1` | 새 이미지의 왼쪽 상단 포인트는 원본 이미지의 왼쪽 상단 포인트와 일치합니다. 필요한 경우 자르기가 발생합니다. |
| RightTopToRightTop | `2` | 새 이미지의 오른쪽 상단 지점은 원본 이미지의 오른쪽 상단 지점과 일치합니다. 필요한 경우 자르기가 발생합니다. |
| RightBottomToRightBottom | `3` | 새 이미지의 오른쪽 하단 지점은 원본 이미지의 오른쪽 하단 지점과 일치합니다. 필요한 경우 자르기가 발생합니다. |
| LeftBottomToLeftBottom | `4` | 새 이미지의 왼쪽 하단 지점은 원본 이미지의 왼쪽 하단 지점과 일치합니다. 필요한 경우 자르기가 발생합니다. |
| CenterToCenter | `5` | 새 이미지의 중심은 원본 이미지의 중심과 일치합니다. 필요한 경우 자르기가 발생합니다. |
| LanczosResample | `6` | a=3. 인 lanczos 알고리즘을 사용하여 리샘플 |
| NearestNeighbourResample | `7` | 가장 가까운 이웃 알고리즘을 사용하여 리샘플링합니다. |
| AdaptiveResample | `8` | 가중 및 혼합 합리적 함수와 lanczos3 보간 알고리즘을 기반으로 하는 적응형 알고리즘을 사용하여 리샘플링합니다. |
| BilinearResample | `9` | 쌍선형 보간을 사용하여 리샘플링합니다. 이미지 사전 필터링은 필요한 경우 리샘플링 전에 노이즈를 제거할 수 있습니다 |
| HighQualityResample | `10` | 고품질 resample |
| CatmullRom | `11` | Catmull-Rom 큐빅 보간법. |
| CubicConvolution | `12` | 큐빅 컨벌루션 보간법 |
| CubicBSpline | `13` | CubicBSpline 큐빅 보간법 |
| Mitchell | `14` | 미첼 큐빅 보간법 |
| SinC | `15` | Sinc(Lanczos3) 큐빅 보간법 |
| Bell | `16` | 벨 보간법 |

### 예

다음 코드는 새로운 SinC 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Bell 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Mitchell 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CatmullRom 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicBSpline 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicConvolution 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


