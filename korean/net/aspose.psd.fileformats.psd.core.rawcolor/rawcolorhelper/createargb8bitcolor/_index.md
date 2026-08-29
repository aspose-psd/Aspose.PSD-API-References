---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RawColorHelper 메서드. 채널당 8비트 ARGB 색상을 생성합니다"
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

채널당 8비트 ARGB 색상을 생성합니다.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | 바이트 | 알파 구성 요소 값 (0-255). |
| r | 바이트 | 레드 구성 요소 값 (0-255). |
| g | 바이트 | 그린 구성 요소 값 (0-255). |
| b | 바이트 | 블루 구성 요소 값 (0-255). |

### 반환 값

새 [`RawColor`](../../rawcolor/) 인스턴스로 ARGB 색상을 나타냅니다.

## 비고

색상 구성 요소는 다음 순서대로 32비트 정수에 패킹됩니다: 알파 (비트 24-31), 레드 (비트 16-23), 그린 (비트 8-15), 그리고 블루 (비트 0-7).

### 또 보기

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Drawing.Color에서 채널당 8비트 ARGB 색상을 생성합니다.

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| drawingColor | 색상 | System.Drawing 색상 |

### 반환 값

새 [`RawColor`](../../rawcolor/) 인스턴스로 ARGB 색상을 나타냅니다.

## 비고

색상 구성 요소는 다음 순서대로 32비트 정수에 패킹됩니다: 알파 (비트 24-31), 레드 (비트 16-23), 그린 (비트 8-15), 그리고 블루 (비트 0-7).

### 또 보기

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


