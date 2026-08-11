---
title: "RawColor.RawColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RawColor 생성자. RawColor 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

새 인스턴스를 초기화합니다 [`RawColor`](../) 클래스의.

```csharp
public RawColor(ColorComponent[] components)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 구성 요소 | ColorComponent[] | 맞춤 색상 구성 요소입니다. |

### 또 보기

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

픽셀 데이터 형식에서 미리 정의된 색상 모드를 사용하여 [`RawColor`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | 픽셀 데이터 형식입니다. |
| colorMode | Int16 | 색상이 따를 모드. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 채널 수가 PixelFormat과 다르며, 채널 인덱스를 가져올 수 없습니다. Components 배열 인수를 사용하여 RawColor를 생성하십시오. |

### 또 보기

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


