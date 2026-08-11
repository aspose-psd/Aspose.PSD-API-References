---
title: "클래스 PixelDataFormat"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.PixelDataFormat 클래스. 픽셀 데이터 형식입니다. 이 객체는 불변 객체입니다."
type: docs
weight: 5720
url: /ko/net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

픽셀 데이터 형식입니다. 이는 불변 객체입니다.

```csharp
public class PixelDataFormat
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | `PixelDataFormat`을 가져옵니다. 각 시안, 마젠타, 옐로우, 블랙에 8비트를 할당한 32비트 픽셀당 형식입니다. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | acmyk를 가져옵니다. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | `PixelDataFormat`을 가져옵니다. 0-255 구간에서 회색조 강도를 나타내는 8비트를 사용한 8비트 픽셀당 형식입니다. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | `PixelDataFormat`을 가져옵니다. 0-255 구간에서 회색조 강도를 나타내는 8비트와 추가 8비트 알파 구성 요소를 포함한 16비트 픽셀당 형식입니다. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | `PixelDataFormat`을 가져옵니다. 빨강, 초록, 파랑 각각에 5비트를 할당하고 알파는 정의되지 않은 16비트 픽셀당 형식입니다. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | `PixelDataFormat`을 가져옵니다. 빨강에 5비트, 초록에 6비트, 파랑에 5비트를 할당하고 알파는 정의되지 않은 16비트 픽셀당 형식입니다. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | `PixelDataFormat`을 가져옵니다. 알파, 빨강, 초록, 파랑 각각에 8비트를 할당하고 알파는 정의되지 않은 24비트 픽셀당 형식입니다. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | `PixelDataFormat`을 가져옵니다. 알파, 빨강, 초록, 파랑 각각에 8비트를 할당하고 알파는 정의되지 않은 24비트 픽셀당 형식입니다. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | `PixelDataFormat`을 가져옵니다. 알파, 빨강, 초록, 파랑 각각에 8비트를 할당한 32비트 픽셀당 형식입니다. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | `PixelDataFormat`을 가져옵니다. 알파, 빨강, 초록, 파랑 각각에 8비트를 할당한 32비트 픽셀당 형식입니다. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | `PixelDataFormat`을 가져옵니다. 알파, 빨강, 초록, 파랑 각각에 16비트를 할당한 64비트 픽셀당 형식입니다. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | `PixelDataFormat`을 가져옵니다. 색상당 1비트 인덱스 형식으로 정의됩니다. 인덱스 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 하기 위한 것입니다. 한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 변환이 필요할 수 있으므로 주의해서 사용하십시오. |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | 색상당 2비트 인덱싱된 `PixelDataFormat`을 가져옵니다. 인덱싱된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 허용하도록 설계되었습니다. 변환이 필요할 수 있으므로 주의해서 사용하십시오(한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱싱된 색상 모델로 변환). |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | 색상당 4비트 인덱싱된 `PixelDataFormat`을 가져옵니다. 인덱싱된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 허용하도록 설계되었습니다. 변환이 필요할 수 있으므로 주의해서 사용하십시오(한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱싱된 색상 모델로 변환). |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | 색상당 8비트 인덱싱된 `PixelDataFormat`을 가져옵니다. 인덱싱된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 허용하도록 설계되었습니다. 변환이 필요할 수 있으므로 주의해서 사용하십시오(한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱싱된 색상 모델로 변환). |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | 밝기(luma), 청색 차이(blue-difference), 적색 차이(red-difference) 색도 성분 각각에 8비트를 사용하여 픽셀당 24비트로 정의된 `PixelDataFormat`을 가져옵니다. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | 밝기(luma), 청색 차이(blue-difference), 적색 차이(red-difference), 검정 색도(black) 각각에 8비트를 사용하여 픽셀당 32비트로 정의된 `PixelDataFormat`을 가져옵니다. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | 픽셀당 비트 수를 가져옵니다. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | 픽셀 데이터 형식 캡션을 가져옵니다. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | 각 채널에 대한 비트 수를 가져옵니다. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | 채널 수를 가져옵니다. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | 픽셀 형식을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | 샘플당 지정된 비트 수를 가진 BGR 색상을 가져옵니다. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | 샘플당 지정된 비트 수를 가진 BGRA 색상을 가져옵니다. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | 샘플당 지정된 비트 수를 가진 CIE Lab 색상을 가져옵니다. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | 샘플당 지정된 비트 수를 가진 CMYK 색상을 가져옵니다. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | 샘플당 지정된 비트 수를 가진 CMYK 색상을 가져옵니다. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | 샘플당 지정된 비트 수를 가진 CMYKA 색상을 가져옵니다. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | 샘플당 지정된 비트 수를 가진 그레이스케일 색상을 가져옵니다. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | 샘플당 지정된 비트 수를 가진 GrayscaleAlpha 색상을 가져옵니다. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | 샘플당 지정된 비트 수를 가진 GrayscaleAlpha 색상을 가져옵니다. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | 샘플당 지정된 비트 수를 가진 RGB 색상을 가져옵니다. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | 샘플당 지정된 비트 수를 가진 RGB 색상을 가져옵니다. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | 샘플당 지정된 비트 수를 가진 RGBA 색상을 가져옵니다. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | 샘플당 지정된 비트 수를 가진 RGBA 색상을 가져옵니다. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | 샘플당 지정된 비트 수를 가진 BGRA 인덱싱 색상을 가져옵니다. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | 샘플당 지정된 비트 수를 가진 YCbCr 색상을 가져옵니다. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | 샘플당 지정된 비트 수를 가진 YCbCr 색상을 가져옵니다. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | 샘플당 지정된 비트 수를 가진 YCCK 색상을 가져옵니다. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | 지정된 Object가 이 인스턴스와 같은지 여부를 판단합니다. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | `PixelDataFormat` 클래스 두 개의 동등성 결과를 반환합니다. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | `PixelDataFormat` 클래스 두 개의 비동등성 결과를 반환합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


