---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RawColorHelper 메서드. 채널당 16비트 ARGB 색상을 생성합니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

채널당 16비트 ARGB 색상을 생성합니다.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | UInt16 | 알파 구성 요소 값 (0-65535). |
| r | UInt16 | 빨간색 구성 요소 값 (0-65535). |
| g | UInt16 | 녹색 구성 요소 값 (0-65535). |
| b | UInt16 | 파란색 구성 요소 값 (0-65535). |

### 반환 값

새 [`RawColor`](../../rawcolor/) 인스턴스로 ARGB 색상을 나타냅니다.

## 비고

색상 구성 요소는 64비트 정수에 다음 순서로 패킹됩니다: 알파 (비트 48-63), 빨강 (비트 32-47), 녹색 (비트 16-31), 파랑 (비트 0-15).

### 또 보기

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


