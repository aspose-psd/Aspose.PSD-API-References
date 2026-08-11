---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RawColorHelper 메서드. 채널당 8비트 CMYK 색상을 생성합니다."
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

채널당 8비트 CMYK 색상을 생성합니다.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | 바이트 | 시안 구성 요소 값 (0-255). |
| m | 바이트 | 마젠타 구성 요소 값 (0-255). |
| y | 바이트 | 노란색 구성 요소 값 (0-255). |
| k | 바이트 | 키(검정색) 구성 요소 값 (0-255). |

### 반환 값

새 [`RawColor`](../../rawcolor/) 인스턴스로 CMYK 색상을 나타냅니다.

## 비고

색상 구성 요소는 32비트 정수에 다음 순서로 패킹됩니다: 시안 (비트 24-31), 마젠타 (비트 16-23), 노란색 (비트 8-15), 키/검정 (비트 0-7).

### 또 보기

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


