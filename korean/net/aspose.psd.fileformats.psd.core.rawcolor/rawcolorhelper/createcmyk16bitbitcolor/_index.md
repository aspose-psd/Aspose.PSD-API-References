---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RawColorHelper 메서드. 채널당 16비트 CMYK 색상을 생성합니다"
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

채널당 16비트 CMYK 색상을 생성합니다.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | UInt16 | 시안 구성 요소 값 (0-65535). |
| m | UInt16 | 마젠타 구성 요소 값 (0-65535). |
| y | UInt16 | 노랑 구성 요소 값 (0-65535). |
| k | UInt16 | 키(검정) 구성 요소 값 (0-65535). |

### 반환 값

새 [`RawColor`](../../rawcolor/) 인스턴스로 CMYK 색상을 나타냅니다.

## 비고

색상 구성 요소는 다음 순서대로 64비트 정수에 패킹됩니다: 시안 (비트 48-63), 마젠타 (비트 32-47), 노랑 (비트 16-31), 그리고 키/검정 (비트 0-15).

### 또 보기

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


